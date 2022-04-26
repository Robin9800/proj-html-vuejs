<template>
<!--HEADER-->
  <header class="flex column">
        <div class="main-header flex">
             <img class="flex" src="img/logo-2.png" alt="logo-2">
        <ul class="flex">
            <li><a href="#">Home</a></li>
            <li><a href="#">About us</a></li>
            <li><a href="#">Feature</a></li>
            <li><a href="#">Testimonials</a></li>
            <li><a href="#">Contact US</a></li>
            <li><a href="#"><i class="fa-solid fa-magnifying-glass"></i></a></li>
            <li><a href="#"><i class="fa-solid fa-cart-shopping"></i></a></li>
            <button>Get Started</button>
        </ul>
        </div>
       
        <!--HEADER JUMBOTRON-->
        <div class="header-jumbotron flex">
            <div class="title-readMore column">
                <h1>The biggest platform for your growth.</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing eoptio doloremque quis voluptatem ipsa eius ipsum </p>
                <button>Read More</button>
            </div>
            <div class="jumbotron">
                <img src="img/508.jpeg" alt="">
            </div>
        </div>
    </header>
</template>

<script>
export default {

}
</script>

<style>
.main-header{
    justify-content: space-around;
}
.main-header img{
    align-self: center;
    height: 40px;
    margin: 0px 100px;
}
ul li{
    margin: 30px 10px;
    font-weight: bold;
    list-style-type: none;
    font-size: 12px;
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
header button{
    margin: 20px;
    padding: 10px;
    color: white;
    background-color: hsl(219deg 100% 61%);
    border: none;
    border-radius: 4px;
}
header button:hover{
    background-color: black;
}
.header-jumbotron{
    height: 54vh;
    background-color: hsl(217deg 100% 97%);
}
.header-jumbotron img{
    height: 480px;
    opacity: 0.6;
    filter: alpha(opacity=60)
}
.title-readMore{
    padding: 40px;
}
.header-jumbotron h1{
    font-size: 40px;
    line-height: 70px;
}
.title-readMore p{
    line-height: 30px;
    font-size: 14px;
}
.title-readMore button{
    margin-left: 0px;
}

</style>