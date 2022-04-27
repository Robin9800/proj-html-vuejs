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
  margin: 0px 220px;
  border: 1px solid black;
  height: auto;
}
button{
    margin: 20px;
    padding: 10px;
    color: white;
    background-color: hsl(219deg 100% 61%);
    border: none;
    border-radius: 4px;
}
button:hover{
    background-color: black;
}
li{
  list-style: none;
}
</style>
