<script>
export default {
  name: "AppCard",
  props: {
    card: Object
  }
}
</script>

<template>
  <div class="card">
    <div class="img-card">
      <img :src="card.thumb" :alt="card.series">
    </div>
    <h4>{{ card.series }}</h4>
  </div>
</template>


<style lang="scss" scoped>
  .card{
    width: calc(100% / 6);
    cursor: pointer;
    padding: 0px 5px 20px;

    .img-card{
      width: 100%;
      padding-bottom: 10px;
        img{
          width: 150px;
          height:150px;
          object-fit: cover;
          object-position: top;
        }
    };
    h4{
      color: white;
      font-size: 0.8rem;
    }
  }
</style>