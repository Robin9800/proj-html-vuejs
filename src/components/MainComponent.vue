<template>
  <main class="flex column border">
      <OnlineMarketingSection/>
      <TricksComponent/>
      <FeaturesComponent/>
      <img src="img/15.png" alt="">
      
  </main>
</template>

<script>
import OnlineMarketingSection from './OnlineMarketingSection.vue'
import TricksComponent from './TricksComponent.vue'
import FeaturesComponent from './FeaturesComponent.vue'
export default {
    name: 'MainComponent',
    
    components: {
        OnlineMarketingSection,
        TricksComponent,
        FeaturesComponent
    }
}
</script>

<style>
main{
    margin-top: 120px;
}
main img{
    color: black;
}
</style>