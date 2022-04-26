<template>
  <header class="flex">
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
        <div class="header-jumbotron"></div>
    </header>
</template>

<script>
export default {

}
</script>

<style>
header{
    justify-content: space-around;
}
header img{
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
    margin: 15px;
    padding: 10px;
    color: white;
    background-color: hsl(219deg 100% 61%);
    border: none;
    border-radius: 4px;
}
header button:hover{
    background-color: black;
}
</style>