<template>
  <div class="latest-card flex">
      <div class="card-info flex column" v-for="(page,index) in LatestCardData" :key="index">
            <div class="latest-image">
            <div class="data f-12">{{page.data}}</div>
            <img :src="page.url" alt="">
        </div>
            <h4>{{page.title}}</h4>
            <p class="f-12">{{page.p}}</p>
      </div>
      
  </div>
</template>

<script>
import LatestCardData from '@/assets/LatestCardData'
export default {
    name: 'LatestCard',
    data(){
        return {LatestCardData}
    }
}
</script>

<style>
.latest-card{
    justify-content: space-around;
    margin: 18px;
}
.card-info{
    width: 280px;
    height: 300px;
    padding: 4px;
    border: 1px solid #00000014;
}
.card-info img{
    width: 100%;
    height: 150px;
}
.card-info h4,p{
    margin-top: 10px;
    padding: 6px;
}
.data{
    position: absolute;
    padding: 10px;
    margin: 6px;
    background-color: white;
}
</style>