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
        <li v-for="post in posts" :key="post.text">
        <a :href="post.url">{{post.text}}</a></li>
        
      </ul>
    </div>
    <div class="services">
      <ul>
        <li><a href="#"><strong>SERVICES</strong></a></li>
        <li v-for="service in services" :key="service.text">
        <a :href="service.url">{{service.text}}</a></li>
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
    name:'TheSecondfooterSection',
    data(){
      return{
        posts:[
          {url:'#', text:'When is it the right time to sell your company?'},
          {url:'#', text:'Personal debt or company debt we explore your option'},
          {url:'#',text:'An interview with a so-called business angel'}
        ],
        services:[
          {url:'#',text:'SMALL BUSINESS LOAN SERVICES'},
          {url:'#',text:'CREDIT RATING ADVICE SERVICES'},
          {url:'#',text:'CROWD FOUNDING SERVICES'},
        ]
      }
    }
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