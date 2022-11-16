<script>

import AppCard from './AppCard.vue';
import seriesDC from '../data/seriesDC'

export default {
  name: 'DCSeries',
  components:{
    AppCard
  },
  data(){
    return{
      seriesDC
    }
  }
}
</script>

<template>
  <section>
    <div class="current-series">
      <AppCard v-for="(card, index) in seriesDC" :key="index" :card="card" />
    </div>
    <button>LOAD MORE</button>
  </section>
</template>


<style lang="scss" scoped>
  section{
    background-color: #1c1c1c;
    text-align: center;
    button{
      padding: 8px 40px;
      margin-bottom: 15px;
      color: white;
      background-color: #0282f9;
      border: none;
      cursor: pointer;
    }
    .current-series{
      width: 70%;
      margin: 0 auto;
      display: flex;
      flex-wrap: wrap;
      padding: 50px;
    }
  }
</style>