<template>
  <div class="latest-title-p flex column">
          <h2 class="text-center">Latest Post</h2>
          <p class="f-12 text-center">If you are planning on developing a product landing.</p>
          <LatestCard/>
    </div>
</template>

<script>
import LatestCard from './LatestCard.vue'
export default {
    name: 'LatestComponent',
    components: {
        LatestCard
    }
}
</script>

<style>
.latest-title-p{
    margin-top: 120px;
}
.latest-title-p h2{
    margin-bottom: 15px;
}
.latest-title-p p{
    margin-bottom: 60px;
}
</style>