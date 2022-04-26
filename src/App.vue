<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import MainComponent from './components/MainComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
  }
}
</script>

<style>
#app{
  margin: 0px 200px;
  border: 1px solid black;
  height: 100vh;
}
</style>
