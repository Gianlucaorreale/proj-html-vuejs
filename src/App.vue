<template>
  <div>
    <MainHeader/>
    <TheJumbotron/>
    <TheClientSection/>
  </div>
</template>

<script>

import MainHeader from './components/MainHeader.vue'
import TheJumbotron from './components/TheJumbotron.vue';
import TheClientSection from './components/TheClientSection.vue';
export default {
  name: 'App',
  components: { MainHeader, TheJumbotron, TheClientSection }
}
</script>

<style lang="scss">

</style>
