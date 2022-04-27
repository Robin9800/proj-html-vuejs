<template>
  <div class="card">
      <h4>{{song.year}}</h4>
      <img :src="song.poster" alt="">
  </div>
</template>

<script>
export default {
    name: 'FeatureCard'
}
</script>

<style>

</style>