<template>
  <section class="container">
    
        <h2>Specialty Services</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque maxime unde ipsam ullam ea,<br> vel voluptas impedit maiores veniam aliquid, ad quaerat officia! Nisi illo dolore, voluptatibus eius quisquam reprehenderit.</p>
    
    <div id="cards-container" >
       <div class="cards">
         <h3>Small Business Loan</h3>
         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate at voluptatum esse consequatur facere maiores accusantium</p>
         <button><a href="#">Learn More</a></button>
       </div>
       <div class="cards">
         <h3>Credit Rating advice</h3>
         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate at voluptatum esse consequatur facere maiores accusantium</p>
         <button><a href="#">Learn More</a></button>
       </div>
       <div class="cards">
         <h3>Fast Crowd Founding</h3>
         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate at voluptatum esse consequatur facere maiores accusantium</p>
         <button><a href="#">Learn More</a></button> 
       </div>
       
    </div>
  </section>
</template>

<script>
   export default{
    name:'TheServicesSection'
   }
</script>

<style lang="scss">
  .container {
    background-color: #F9F9F9;
    height: 500px;
    
    p{
       text-align: center;
    }
    h2{
        text-align: center;
        padding: 40px;
    }
    #cards-container{
        display: flex;
        justify-content: center;
        margin: 100px 0px;
        .cards{
            height: 100px;
            margin: 0px 20px;
            width: calc(100% / 3 - 20px);
            background-color: white;
            display: flex;
            flex-direction: column;
            button{
              background-color: #5ADDCD;
              border-color: #5ADDCD;
             a{
                text-decoration: none;
                 color: white;
              }
            }
            h3{
              text-align: center;
            }
        }
    }
    
  }
</style>