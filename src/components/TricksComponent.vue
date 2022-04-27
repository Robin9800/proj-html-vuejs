<template>
   <div class="tricks-jumbotron flex">

            <div class="title-tricks column">
                <h1>Get tips tricks on how to skyrocket your sales.</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing eoptio doloremque quis voluptatem ipsa eius ipsum </p>
                
                <div class="flex title-p">
                    <img src="img/510.png" alt="">
                    <div class="didascalie flex column">
                        <h4>Reporting Analysis</h4>
                        <p>It is a long established fact that  a reader will  a reader will be distracted long established fact that a reader wi.</p>
                    </div>
                </div>

                <div class="flex title-p">
                    <img src="img/511.png" alt="">
                    <div class="didascalie flex column">
                        <h4>Technical SEO Audit</h4>
                        <p>It is a long established fact that  a reader will  a reader will be distracted long established fact that a reader wi.</p>
                    </div>
                </div>
            </div>
             
            <div class="tricks-image">
                <img src="img/509.jpeg" alt="">
            </div>
        </div>
</template>

<script>
export default {
    name: 'TricksComponent'
}
</script>

<style>
.tricks-jumbotron{
    margin-top: 50px;
}
.tricks-jumbotron h1{
    margin-bottom: 20px;
}
.tricks-jumbotron img{
    height: 60px;
}
.title-tricks{
    padding: 40px;
}
.title-tricks p{
    line-height: 30px;
    font-size: 14px;
}
.title-p{
    transition: 1s;
    margin: 40px auto auto auto;
}
.title-p img{
    align-self: center;
}
.title-p:hover{
    box-shadow: 10px 10px 5px #dedede;
    transform: scale(1.1)
}
.title-p h4:hover{
    color: hsl(219deg 100% 61%);
}
.didascalie{
    margin-left: 20px;
}
.didascalie h4{
    margin-bottom: 10px;
}
.tricks-image img{
    height: 360px;
    margin-right: 100px;
    margin-top: 100px
}
</style>