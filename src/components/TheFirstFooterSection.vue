<template>
  <section>
    <div id="bg">
        <div id="first-footer">
          <h2>Ready to talk?</h2>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quidem laudantium repudiandae delectus adipisci </p>
        </div>
        <button><a href="#">LET'S TALK</a></button>
    </div>
    
  </section>
</template>

<script>
  export default {
    name:'TheFirstFooterSection'
  }
</script>

<style lang="scss">
  #bg{
    background-image: url(../assets/img/ready_to_talk_cta_bg.jpg);
    background-size: cover;
    height: 400px;
     #first-footer{
    
    display: flex;
    justify-content: center;
    flex-direction: column;
    h2{
        font-size: 3rem;
        color: white;
        text-align: center;
    }
    p{
        color: lightgray;
        text-align: center;
    }
   
   }
    button{
    background-color: #5ADDCD;
    border-color: #5ADDCD;
    border-radius: 20px;
    margin-left: 700px;
    a{
        text-decoration: none;
        color: white;
    }
   }
  }
   
</style>