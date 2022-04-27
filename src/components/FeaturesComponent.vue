<template>
    
  <div class="features flex column">
      <img src="img/14.png" alt="">
      <div class="explore flex">
          <div class="h1-p flex column">
              <h1>Populare features that ypur business needs</h1>
            <p class="f-14">Lorem ipsum dolor sit amet consectetur adipisicing eoptio doloremque quis voluptatem  <br> ipsa eius ipsum </p>
          </div>
            <button>Explore more features</button>
      </div>
      <!--FEATURES CARDS-->
      <ul class="cards flex">
          <li class="card" v-for="(page,index) in cards" :key="index">
              <h4 class="f-14">{{page.name}}</h4>
              <img :src="page.url" alt="">
            </li>
      </ul>
        
  </div>
</template>

<script>
import cards from '@/assets/cards'
export default {
    name: 'FeaturesComponent',
    data(){
        return {cards}
    }
}
</script>

<style>
.features{
    margin: 120px 50px
}
.features img{
    height: 400px;
    background-color: hsl(212deg 100% 97%);
    border-radius: 500px;
}
.features ul{
    flex-wrap: wrap;
}
.features li{
     box-shadow:  2px  2px 2px #dedede,
              -1px -1px 2px #dedede,
               1px -1px 2px #dedede,
              -1px 1px 2px #dedede;
    border-radius: 4px;
    padding: 10px 20px;
    text-align: start;
    margin: 10px 20px;
}
.features li:hover{
    background-color: #6CDAC1;
}

.explore{
    justify-content: space-around;
}
.card{
    width: 200px;
    height: 120px;
    margin: 20px;
}
.cards{
    margin-top: 40px;
    justify-content: center;
}
.explore h1{
    margin-bottom: 20px;
    font-size: 26px;
}
.explore button{
    margin: 30px;
    padding: 10px;
}
</style>