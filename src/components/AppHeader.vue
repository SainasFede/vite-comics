<script>
export default {
  name: 'AppHeader',
  data(){
    return{
      menu:[
        {
          text: 'CHARACTERS',
          href: '#',
          current: false
        },

        {
          text: 'COMICS',
          href: '#',
          current: false
        },

        {
          text: 'MOVIES',
          href: '#',
          current: false
        },

        {
          text: 'TV',
          href: '#',
          current: false
        },

        {
          text: 'GAMES',
          href: '#',
          current: false
        },

        {
          text: 'COLLECTIBLES',
          href: '#',
          current: false
        },

        {
          text: 'VIDEOS',
          href: '#',
          current: false
        },

        {
          text: 'FANS',
          href: '#',
          current: false
        },

        {
          text: 'NEWS',
          href: '#',
          current: false
        },

        {
          text: 'SHOP',
          href: '#',
          current: false
        }
      ]
    }
  }

}
</script>

<template>

  <header>

    <div class="logo">
      <img src="/dc-logo.png" alt="DC">
    </div>
  
    <nav>
      <ul>
        <li 
        v-for="(link, index) in menu"
        :key="index"><a href="link.href"><h4>{{link.text}}</h4></a> </li>
      </ul>
    </nav>

  </header>

</template>


<style lang="scss" scoped>
  header{
    width: 70%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    nav{
      ul{
        display: flex;
        li{
          margin: 15px;
          list-style: none;
          a{
            text-decoration: none;
            display: inline-block;
            color: #303030;
          }
        }
      }
    }
  }

</style>