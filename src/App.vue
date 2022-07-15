<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
import '@fortawesome/fontawesome-free/js/all.js';
import '@/assets/scss/common.scss'
import '@/assets/scss/vars.scss'
import HeaderComponent from './components/HeaderComponent.vue'
import MainComponent from './components/MainComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
    
    // HelloWorld
  }
}
</script>

<style lang="scss">
#app {
}
</style>
