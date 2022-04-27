<template>
  <div class="testimonial-card flex column text-center">
      <img src="img/26.jpeg" alt="">
      <h3>Julian Aann - <span>COO Sofbox</span></h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit amet consectetur adipisic. Dignissimos laboriosam nullallenduseritatis ea.</p>
  </div>
</template>

<script>
export default {
    name: 'TestimonialCard'
}
</script>

<style>
.testimonial-card{
    width: 400px;
    height: 250px;
    padding: 10px;
    box-shadow:  2px  2px 2px #dedede,
              -1px -1px 2px #dedede,
               1px -1px 2px #dedede,
              -1px 1px 2px #dedede;
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