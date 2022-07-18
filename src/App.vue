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

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
  },
    //       data() {
    //     return {
    //         navLinks: [
    //             {
    //                 text: 'Home',
    //                 url: '#',
    //                 current: false,
    //                 apply: false
    //             },
    //             {
    //                 text: 'who We Are',
    //                 url: '#',
    //                 current: true,
    //                 apply: false
    //             },
    //             {
    //                 text: 'What We Do',
    //                 url: '#',
    //                 current: false,
    //                 apply: false
    //             },
    //             {
    //                 text: 'Where We Work',
    //                 url: '#',
    //                 current: false,
    //                 apply: false
    //             },
    //             {
    //                 text: 'Carrers Apply',
    //                 url: '#',
    //                 current: false,
    //                 apply: false
    //             },
    //             {
    //                 text: 'News',
    //                 url: '#',
    //                 current: false,
    //                 apply: false
    //             },
    //         ],
    //     };
    // }
}
</script>

<style lang="scss">
#app {
}
</style>
