<template>
  <main class="flex column border">
      <OnlineMarketingSection/>
      <TricksComponent/>
      <FeaturesComponent/>
      <TestimonialComponent/>
      <LatestComponent/>
  </main>
</template>

<script>
import OnlineMarketingSection from './OnlineMarketingSection.vue'
import TricksComponent from './TricksComponent.vue'
import FeaturesComponent from './FeaturesComponent.vue'
import TestimonialComponent from './TestimonialComponent.vue'
import LatestComponent from './LatestComponent.vue'

export default {
    name: 'MainComponent',
    
    components: {
        OnlineMarketingSection,
        TricksComponent,
        FeaturesComponent,
        TestimonialComponent,
        LatestComponent
    }
}
</script>

<style>
main{
    margin: 120px 40px 0px 40px;
    z-index: 1;

}
</style>