<template>
<!--HEADER-->
  <header class="flex column">
        <div class="main-header flex">
             <img class="flex" src="img/logo-2.png" alt="logo-2">
        <ul class="flex">
            <li class="f-12" v-for="(page,index) in navigation" :key="index"><a href="#">{{page.name}}</a></li>
            <li class="f-12"><a href="#"><i class="fa-solid fa-magnifying-glass"></i></a></li>
            <li class="f-12"><a href="#"><i class="fa-solid fa-cart-shopping"></i></a></li>
            <button>Get Started</button>
        </ul>
        </div>
       
        <!--HEADER JUMBOTRON-->
        <div class="header-jumbotron flex">
            <div class="title-readMore column">
                <h1>The biggest platform for your growth.</h1>
                <p class="f-14">Lorem ipsum dolor sit amet consectetur adipisicing eoptio doloremque quis voluptatem ipsa eius ipsum </p>
                <button>Read More</button>
            </div>
            <div class="jumbotron">
                <img src="img/27-1.png" alt="">
            </div>
        </div>
    </header>
</template>

<script>
import navigation from '@/assets/navigation'

export default {
    name: 'HeaderComponent',
    data(){
        return {navigation}
    }
}
</script>

<style>
header{
    margin: 0px 160px;
}
.main-header{
    justify-content: space-around;
}
.main-header img{
    align-self: center;
    height: 40px;
    margin: 0px 100px;
}
header ul li{
    margin: 30px 10px;
    font-weight: bold;
    list-style-type: none;
}
ul li a{
    text-decoration: none;
    color: black;
    padding-bottom: 10px;
}
ul li a:hover{
    color: hsl(209deg 98% 49%);
    border-bottom: 2px solid hsl(209deg 98% 49%);
}

.header-jumbotron{
    height: 54vh;
    background-color: hsl(217deg 100% 97%);
    border-radius: 10px;
}
.header-jumbotron img{
    height: 400px;
    margin-top: 20px;
}
.title-readMore{
    padding: 40px;
}
.header-jumbotron h1{
    font-size: 38px;
    line-height: 70px;
}
.title-readMore p{
    line-height: 30px;
}
.title-readMore button{
    margin-left: 0px;
}

</style>