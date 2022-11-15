<script>
export default {
  name: 'AppBlu',
  data(){
    return{
      menu:[
        {
          img: "buy-comics-digital-comics.png",
          text: "DIGITAL COMICS",
        },
        {
          img: "buy-comics-merchandise.png",
          text: "DC MERCHANDISE",
        },
        {
          img: "buy-comics-subscriptions.png",
          text: "SUBSCRIPTION",
        },
        {
          img: "buy-comics-shop-locator.png",
          text: "COMIC SHOP LOCATOR",
        },
        {
          img: "buy-dc-power-visa.svg",
          text: "DC POWER VISA",
        },
      ]
    }
  },
  methods: {
    getPathImage(imageName) {
      return new URL(`../assets/img/${imageName}`, import.meta.url).href;
    }
  }
}
</script>

<template>
  <section class="cards">
    <div class="list-cards">
      <ul>
        <li v-for="(link, index) in menu" :key="index">
          <div class="img-card">
            <img :src="getPathImage(link.img)" :alt="link.text" />
          </div>
          <a href="#">{{ link.text }}</a>
        </li>
      </ul>
    </div>
  </section>
</template>


<style lang="scss" scoped>
  .cards{
    width: 100%;
    height: 160px;
    background-color: #0282f9;
    .list-cards{
      width: 70%;
      height: 100%;
      margin: 0 auto;
      ul{
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100%;
        li{
          display: flex;
          justify-content: center;
          align-items: center;
          width: calc(100% / 5);
          .img-card{
            width: 60px;
            height: 70px;
            margin-right: 10px;
            &:hover{
              cursor: pointer;
            }
            img{
              width: 100%;
              height: 100%;
            }
          }
          a{
            text-decoration: none;
            color: white;
            font-size: 0.9rem;
          }
        }
      }
    }
  }
</style>