<template>
  <div class="latest-card flex column border">
      <div class="latest-image">
          <div class="data f-12">November 28, 2019</div>
          <img src="img/19.jpeg" alt="">
      </div>
      <h4>Life Lack Meaning</h4>
      <p class="f-12">It is a long established that a reader will be distracted by the readable</p>
  </div>
</template>

<script>
export default {
    name: 'LatestCard'
}
</script>

<style>
.latest-card{
    width: 280px;
    height: 300px;
    padding: 10px;
}
.latest-image img{
    width: 100%;
    height: 150px;
}
.latest-card h4{
    margin-top: 20px;
}
.data{
    position: absolute;
    padding: 10px;
    margin: 6px;
    background-color: white;
}
</style>