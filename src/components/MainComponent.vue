<template>
  <main class="flex column border">
      <OnlineMarketingSection/>
      <TricksComponent/>
  </main>
</template>

<script>
import OnlineMarketingSection from './OnlineMarketingSection.vue'
import TricksComponent from './TricksComponent.vue'
export default {
    name: 'MainComponent',
    
    components: {
        OnlineMarketingSection,
        TricksComponent
    }
}
</script>

<style>
main{
    margin-top: 120px;
}
</style>