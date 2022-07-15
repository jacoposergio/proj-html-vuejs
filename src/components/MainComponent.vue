<template>
  <main>
    <OurAgency/>
    <OurServices/>
    <OurWork/>
    <OurPlans/>
    <OurNews/>
    <OurFeedback/>
    <CallToAction/>

  </main>
</template>

<script>
import OurAgency from '../components/OurAgency.vue'
import OurServices from '../components/OurServices.vue'
import OurWork from '../components/OurWork.vue'
import OurPlans from '../components/OurPlans.vue'
import OurNews from '../components/OurNews.vue'
import OurFeedback from '../components/OurFeedback.vue'
import CallToAction from '../components/CallToAction.vue'


export default {
     name: 'MainComponent',
     components: {
          OurAgency,
          OurServices,
          OurWork,
          OurPlans,
          OurNews,
          OurFeedback,
          CallToAction
  }

}
</script>

<style lang="scss" scoped>

</style>