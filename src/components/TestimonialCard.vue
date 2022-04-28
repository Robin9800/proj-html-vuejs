<template>
  <div class="testimonial-card flex text-center">
      <div class="container"  v-for="(page,index) in TestimonialCardData" :key="index">
          <img :src="page.url" alt="">
            <h3>{{page.name}} - <span>{{page.job}}</span></h3>
            <p>{{page.info}}</p>
      </div>
              
      
  </div>
</template>

<script>
import TestimonialCardData from '@/assets/TestimonialCardData'
export default {
    name: 'TestimonialCard',
    data(){
        return {TestimonialCardData}
    }
}
</script>

<style>
.testimonial-card{
   justify-content: center;
}
.container{
     width: 400px;
    height: 250px;
    padding: 10px;
    margin: 20px;
    box-shadow:  2px  2px 2px #dedede,
              -1px -1px 2px #dedede,
               1px -1px 2px #dedede,
              -1px 1px 2px #dedede;
}
.container:hover{
    box-shadow: 10px 10px 5px #dedede;
    transform: scale(1.1)
}
.testimonial-card img{
    align-self: center;
    height: 50px;
    width: 50px;
    margin: 22px;
    border-radius: 50px;
}
.testimonial-card p{
    font-size: 14px;
    margin: 20px auto;
    line-height: 24px;
}
.testimonial-card span{
    color: grey;
}
</style>