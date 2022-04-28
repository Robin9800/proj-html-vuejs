<template>
  <div class="testimonial flex column">
      <img class="testimonial-bar" src="img/15.png" alt="">
      <div class="testimonial-title-p text-center flex column">
          <h2>Our Testimonials</h2>
            <p class="f-12">Lorem ipsum, dolor sit amet consecteturusationus nihil iste fugiat hic odit, tempore, minus laborum porro sed!</p>
      </div>
      <TestimonialCard/>
      
  </div>
</template>
<script>
import TestimonialCard from './TestimonialCard.vue'
export default {
    name: 'TestimionalComponent',
    components:{
        TestimonialCard
    }
}
</script>

<style>
.testimonial-bar{
    height: 300px;
    background: linear-gradient(#f2f7ff, white);
    z-index: -1;
}
.testimonial-title-p{
    width: 550px;
    align-self: center;
    margin-bottom: 80px;
}
.testimonial-title-p h2,p{
    margin: 10px auto;
    align-self: center;
}
</style>