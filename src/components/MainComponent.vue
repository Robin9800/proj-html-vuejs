<template>
  <main class="flex column">
      <OnlineMarketingSection/>
      <TricksComponent/>
      <FeaturesComponent/>
      <TestimonialComponent/>
      <LatestComponent/>
      <ContactComponent/>
  </main>
</template>

<script>
import OnlineMarketingSection from './OnlineMarketingSection.vue'
import TricksComponent from './TricksComponent.vue'
import FeaturesComponent from './FeaturesComponent.vue'
import TestimonialComponent from './TestimonialComponent.vue'
import LatestComponent from './LatestComponent.vue'
import ContactComponent from './ContactComponent.vue'

export default {
    name: 'MainComponent',
    
    components: {
        OnlineMarketingSection,
        TricksComponent,
        FeaturesComponent,
        TestimonialComponent,
        LatestComponent,
        ContactComponent,
    }
}
</script>

<style>
main{
    margin: 160px 160px 30px 160px;
    z-index: 1;
}
</style>