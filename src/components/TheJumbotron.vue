<template>
 <div id="jumbo">
   <p>Right People Right investments</p>
 </div>
</template>

<script>
export default {
  name: 'TheJumbotron',
  
}
</script>

<style lang="scss">
  #jumbo{
    margin-top: 50px;
    height: 700px;
    background-image: url(../assets/img/home_finance_slider_bg.jpg);
    background-size: cover;
    p{
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      font-size: 3rem;
    }
  }
</style>