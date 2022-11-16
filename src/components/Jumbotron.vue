<script>
export default {
  name: 'Jumbotron'
}
</script>

<template>
  <div class="jumbotron">
    <button>CURRENT SERIES</button>
  </div>
</template>



<style lang="scss" scoped>
 .jumbotron{
  height: 400px;
  background-image: url('../assets/img/jumbotron.jpg');
  background-size: cover ;
  position: relative;
  button{
    padding: 10px 15px;
    font-size: 1rem;
    color: white;
    background-color: #0282f9;
    border: none;
    cursor: pointer;
    position: absolute;
    left: 100px;
    buttom: -50px;
  }
 }
</style>