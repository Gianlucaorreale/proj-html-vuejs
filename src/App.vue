<template>
  <div>
    <MainHeader/>
    <TheJumbotron/>
  </div>
</template>

<script>

import MainHeader from './components/MainHeader.vue'
import TheJumbotron from './components/TheJumbotron.vue';
export default {
  name: 'App',
  components: { MainHeader, TheJumbotron }
}
</script>

<style lang="scss">

</style>
