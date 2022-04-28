<template>
  <footer class="flex">

    <!--LOGO-->
    <div class="logo flex column">
      <img src="img/35.png" alt="">
      <p>It is a long established fact that  a reader will  a reader will be distracted.</p>
      <p class="copyright">Copyright @ 2018 <a href="#">Sofbox</a></p>
    </div>

    <!--INFO UTILI-->
      <div class="info flex">
        <ul class="info-list flex column">
          <h4>Menu</h4>
          <li class="f-12" v-for="(page,index) in InfoUtili" :key="index"><a href="#">{{page.name1}}</a></li>
        </ul>
        <ul class="info-list flex column">
          <h4>About Us</h4>
          <li class="f-12" v-for="(page,index) in InfoUtili" :key="index"><a href="#">{{page.name2}}</a></li>
        </ul>
        <ul class="info-list flex column">
          <h4>Quick Links</h4>
          <li class="f-12"  v-for="(page,index) in InfoUtili" :key="index"><a href="#">{{page.name1}}</a></li>
        </ul>
      </div>
      <button id="ancora"><a href=""><i class="fa-solid fa-angle-up"></i></a></button>
  </footer>
</template>

<script>
import InfoUtili from '@/assets/InfoUtili'
export default {
  
  name: 'FooterComponent',
  data(){
    return {InfoUtili}
  }
}
</script>

<style>
footer{
  justify-content: space-around;
  border-top: 1px solid #00000014;
  padding: 50px;
}
.logo img{
  width: 120px;
  margin-bottom: 10px;
}
.logo{
  width: 220px;
  margin-left: 100px;
}
.copyright{
  margin-top: 40px;
}
.copyright a{
  text-decoration: none;
  color: hsl(219deg 100% 63%);
}
.info{
  margin-right: 160px;
}
.info-list{
  margin: 0px 60px;
  line-height: 30px;
}
.info h4{
  margin-bottom: 10px;
}
#ancora{
  border-radius: 100px;
  height: 50px;
  width: 50px;
  background-color: hsl(0deg 0% 70%);
  align-self: flex-end;
  margin: 0px;
}
#ancora :active{
  color:hsl(219deg 100% 63%);
}

#ancora i{
  font-size: 24px;
}

</style>