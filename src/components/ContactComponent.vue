<template>
  <div class="contact-container flex column">
      <h2 class="text-center">Contact with our team</h2>
      <p class="f-12 as-center">If you are planning on developing a product landing.</p>

        <!--MAP-->
      <div class="map-info-container flex">
          <div class="map flex column">
              <!--MAPPA INDIRIZZO-->
              <div class="indirizzo flex">
                    <div class="indirizzo-via">
                        <h4 class="f-12">Storey Ave</h4>
                        <p class="f-12">San Francisco, California 94129</p>
                        <a href="#">Visualizza mappa più grande</a>
                    </div>

                    <div class="indirizzo-strada flex column">
                        <i class="fa-solid fa-location-arrow"></i>
                        <a href="#">Indicazioni</a>
                    </div>
              </div>

              <!--POSIZIONE-->
            <i class="fa-solid fa-location-dot position"></i>

            <img src="img\StaticMapService.GetMapIma.png" alt="">

            <!--ZOOM-->
            <div class="zoom flex column">
                <a href="#"><i class="fa-solid fa-plus"></i></a>
                <a href="#"><i class="fa-solid fa-minus"></i></a>
            </div>
          </div>
            
            <!--INPUT-->
          <div class="input flex column">
              <img src="img/35.png" alt="">
              <h2>980 Shore St. Fond Du Lac, WI 54935</h2>
              <p>0 1223 456  789</p>
              <p>mail@sofbox.com</p>

              <!--SOCIAL-->
              <div class="social flex">
                  <a href="#"><i class="fa-brands fa-facebook"></i></a>
                  <a href="#"><i class="fa-brands fa-twitter"></i></a>
                  <a href="#"><i class="fa-brands fa-github"></i></a>
                  <a href="#"><i class="fa-brands fa-instagram"></i></a>
              </div>

              <h1 class="f-20">Get in touch</h1>
              <div class="input-name-email flex between">
                  <input class="name" type="text" placeholder="Your Name">
                  <input class="email" type="text" placeholder="Your Email">
              </div>
              <input class="subject" type="text" placeholder="Your Subject">
              <input class="message" type="text" placeholder="Your Message">
              <button class="send">Send Message</button>
          </div>
      </div>
    </div>
      
</template>

<script>
export default {
    name:'ContactComponent'
}
</script>

<style>
.contact-container{
    margin: 120px 20px 20px 20px;
}
.map-info-container{
    margin: 60px 50px;
    justify-content: space-around;
}
.indirizzo{
    justify-content: space-between;
    padding: 10px;
    margin: 6px;
    font-size: 12px;
    width: 19%;
    position: absolute;
    background-color: white;
}
.indirizzo p{
    padding: 0px;
    margin: 0px;
}
.map img{
    height: 360px;
}
.position{
    position: absolute;
    color: red;
    margin-top: 150px;
    align-self: center;
    font-size: 30px;
}
.indirizzo-via a,.indirizzo-strada a{
    text-decoration: none;
    color: hsl(213deg 72% 60%);
}
.indirizzo-strada i{
    color: hsl(213deg 72% 64%);
    align-self: center;
}
.zoom{
    position: absolute;
    background-color: white;
    color: grey;
    border-radius: 1px;
    align-self: flex-end;
    padding: 6px;
    margin: 8px;
}
.input{
    width: 280px;
    margin-right: 100px;
}
.input img{
    height: 32px;
    width: 100px;
    margin-bottom: 20px;
}
.input h2,p{
    font-size: 14px;
    line-height: 26px;
    margin: 0px;
    padding: 0px;
    align-self: baseline
}
.social{
    margin-bottom: 16px;
}
.social i{
    color: hsl(219deg 100% 61%);
    padding: 8px;
    margin: 20px 4px;
    border: 1px solid #00000014;
    border-radius: 4px;
}
.social i:hover{
    background-color:  hsl(219deg 100% 61%);
    color: white;
}
.input input{
    font-size: 12px;
    padding: 4px 6px;
    margin: 10px 0px;
    border-color:#00000014 ;
}
.name,.email{
    width: 120px;
}
.subject{
    width: 100%;
}
.message{
    width: 100%;
    height: 200px;
    justify-content: baseline;
}
.send{
    width: 125px;
    margin: 10px 0px;
    padding: 12px;
}

</style>