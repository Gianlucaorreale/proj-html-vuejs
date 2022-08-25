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
    <TheSecondfooterSection/>
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
import TheSecondfooterSection from './components/TheSecondfooterSection.vue';

export default {
  name: 'App',
  components: { MainHeader,
                TheJumbotron, 
                TheClientSection, 
                TheFinancialSection, 
                TheServicesSection, 
                TheNumbersSection, 
                TheFeedbackSection, 
                TheFirstFooterSection, 
                TheSecondfooterSection }
}
</script>

<style lang="scss">
  body{
  font-family: 'Raleway', sans-serif;
}
</style>
