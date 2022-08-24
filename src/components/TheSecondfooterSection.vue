<template>
  <section id="second-footer-container">
   <ul>
    <li>
       <img src="../assets/img/finance_logo_footer.png" alt="finance logo">
    </li>
   </ul>
    <div class="recent-posts">
      <ul>
        <li><a href="#"><strong>RECENT POSTS</strong></a></li>
        <li><a href="#">When is it the right time to sell your company?</a></li>
        <li><a href="#">Personal debt or company debt we explore your option</a></li>
        <li><a href="#">An interview with a so-called business angel</a></li>
      </ul>
    </div>
    <div class="services">
      <ul>
        <li><a href="#"><strong>SERVICES</strong></a></li>
        <li><a href="#">SMALL BUSINESS LOAN SERVICES</a></li>
        <li><a href="#">CREDIT RATING ADVICE SERVICES</a></li>
        <li><a href="#">CROWD FOUNDING SERVICES</a></li>
      </ul>
    </div>
    <div class="latest">
      <ul>
        <li><a href="#">LATEST</a></li>
      </ul>
    </div>
  </section>
</template>

<script>
  export default{
    name:'TheSecondfooterSection'
  }
</script>

<style lang="scss">
  #second-footer-container{
    background-color: black;
    display: flex;
    justify-content: flex-start;
    li{
      list-style-type: none;
      padding: 10px;
      a{
        text-decoration: none;
        color: white;
      }
    }
  }
</style>