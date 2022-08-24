<template>
  <div>
    <MainHeader/>
    <TheJumbotron/>
    <TheClientSection/>
    <TheFinancialSection/>
    <TheServicesSection/>
    <TheNumbersSection/>
    <TheFeedbackSection/>
    <TheFirstFooterSection/>
  </div>
</template>

<script>

import MainHeader from './components/MainHeader.vue'
import TheJumbotron from './components/TheJumbotron.vue';
import TheClientSection from './components/TheClientSection.vue';
import TheFinancialSection from './components/TheFinancialSection.vue';
import TheServicesSection from './components/TheServicesSection.vue';
import TheNumbersSection from './components/TheNumbersSection.vue';
import TheFeedbackSection from './components/TheFeedbackSection.vue';
import TheFirstFooterSection from './components/TheFirstFooterSection.vue';
export default {
  name: 'App',
  components: { MainHeader, TheJumbotron, TheClientSection, TheFinancialSection, TheServicesSection, TheNumbersSection, TheFeedbackSection, TheFirstFooterSection }
}
</script>

<style lang="scss">

</style>
