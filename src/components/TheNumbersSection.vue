<template>
   <section id="container" >
     <div class="left-sec">
        <p>Investments Numbers</p>
        <h2>Making an impact in our communities</h2>
        <button><a href="#">Learn more</a></button>
     </div>
     <div class="c-sec">
        <p class="numbers">86%</p>
        <p class="numbers">92%</p>
    </div>
     <div class="right-sec">
        <p class="numbers">94%</p>
        <p class="numbers">100%</p>
    </div>
   </section>
</template>

<script>
  export default {
    name: 'TheNumbersSection'
  }
</script>

<style lang="scss">
  .left-sec{
     height: 300px ;
     width: calc(100% / 3);
     background-image: url(../assets/img/counters-bg-image.jpg);
     background-size: cover;
     
     
     h2,p{
        margin-top: 50px;
        color: white;
        text-align: center;
       }
     button{
        border-radius: 20px;
        background-color: #5ADDCD;
        border-color: #5ADDCD;
        margin-left: 200px;
        a{
            text-decoration: none;
            color: white;
        }
     }
  }
  .c-sec, .right-sec{
    width: calc(100 / 3);
    height: 300px;
   
    .numbers{
        font-size: 3rem;
        margin: 100px 100px;
        
        color: blue;
    }
  }
</style>