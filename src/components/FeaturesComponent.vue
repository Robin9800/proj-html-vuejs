<template>
  <div class="features flex column">
      <div class="explore flex">
          <div class="h1-p flex column">
              <h1>Populare features that ypur business needs</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing eoptio doloremque quis voluptatem ipsa eius ipsum </p>
          </div>
            <button>Explore more features</button>
      </div>
      <!--FEATURES CARDS-->
      <ul class=" cards flex">
          <li  v-for="(page,index) in cards" :key="index"><h4>{{page.name}}</h4></li>
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
    justify-content: space-between;
}
.cards{
    margin-top: 40px;
    justify-content: center;
}
.cards h4{
    font-size: 14px;
}
.explore h1{
    margin-bottom: 20px;
    font-size: 26px;
}
.explore p{
    font-size: 14px;
}
.explore button{
    padding: 10px;
}
</style>