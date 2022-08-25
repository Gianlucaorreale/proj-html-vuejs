<template>
  
  <section id="nav">
    <ul>
        <li><img src="../assets/img/finance_logo_1x.png" alt="logo"></li>
    </ul>
    <ul>
        <li v-for="nav in navs" :key="nav.text">
        <a :href="nav.url">{{nav.text}}</a></li>
        <li><button><a href="#">CONTACT</a></button></li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'MainHeader',
  data(){
    return{
      navs:[
        {url:'#', text:'HOME'},
        {url:'#', text:'ABOUT'},
        {url:'#', text:'SERVICES'},
        {url:'#', text:'PACKAGES'},
        {url:'#', text:'INSIGHT'},
      ]
    }
  }
}
</script>

<style lang="scss">
#nav{
    display: flex;
    background-color: white;
    justify-content: space-between;
    align-items: center;
    height: 50px;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;

    ul {
    display:flex;
    list-style-type: none;
    img{
        height: 30px;
    }
    
    li{
     margin-right: 10px;
     a:hover{
        color: dodgerblue;
        background-color: lightgray;
     }
     button{
      background-color: #5ADDCD;
      border-color: #5ADDCD;
      border-radius: 20px;
     }
     a{
        text-decoration: none;
        color: gray;
      }
    }
  }
}


</style>
