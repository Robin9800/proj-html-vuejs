<template>
  <main class="flex column border">
      <OnlineMarketingSection/>
      <TricksComponent/>
      <FeaturesComponent/>
      <TestimonialComponent/>
      
  </main>
</template>

<script>
import OnlineMarketingSection from './OnlineMarketingSection.vue'
import TricksComponent from './TricksComponent.vue'
import FeaturesComponent from './FeaturesComponent.vue'
import TestimonialComponent from './TestimonialComponent.vue'

export default {
    name: 'MainComponent',
    
    components: {
        OnlineMarketingSection,
        TricksComponent,
        FeaturesComponent,
        TestimonialComponent
    }
}
</script>

<style>
main{
    margin-top: 120px;
}
</style>