<template>
  <div class="online-marketing-section flex">
          <img src="img/24.png" alt="">
          <div class="marketing-card flex column">
              <h3>Online Marketing</h3>
              <p>It is a long established fact that a reader will be distracted.</p>
              <ul>
                  <li v-for="(page, index) in marketingCards" :key="index"><i class="fa-solid fa-check"></i>{{page.name}}</li>
              </ul>
          </div>

          <img src="img/24.png" alt="">
          <div class="marketing-card flex column">
              <h3>Online Marketing</h3>
              <p>It is a long established fact that a reader will be distracted.</p>
               <ul>
                  <li v-for="(page, index) in marketingCards" :key="index"><i class="fa-solid fa-check"></i>{{page.name}}</li>
              </ul>
          </div>

          <img src="img/24.png" alt="">
          <div class="marketing-card flex column">
              <h3>Online Marketing</h3>
              <p>It is a long established fact that a reader will be distracted.</p>
               <ul>
                  <li v-for="(page, index) in marketingCards" :key="index"><i class="fa-solid fa-check"></i>{{page.name}}</li>
              </ul>
          </div>
      </div>
</template>

<script>
import marketingCards from '@/assets/marketingCards'
export default {
    name: 'OnlineMarketingSection',
    data(){
        return {marketingCards}
    },
}
</script>

<style>
.online-marketing-section{
    margin: 40px 50px;
}
.online-marketing-section img{
    height: 60px;
    margin-right: 20px;
}
.marketing-card p{
    line-height: 28px;
    margin: 10px auto;
    font-size: 12px;
}
.marketing-card li{
     font-weight: bold;
    list-style-type: none;
    font-size: 12px;
    margin-left: 0px;
    line-height: 30px;
    
}
.marketing-card i{
    margin-right: 4px;
    color: hsl(209deg 98% 49%);
}
</style>