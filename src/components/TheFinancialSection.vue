<template>
 <section id="container" >
    <div id="left-sec">
        <h2>Cloud Based Finance</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deleniti eveniet cum nihil doloremque id dignissimos natus asperiores dicta? Dolor officiis nulla tempore ducimus impedit corrupti? Amet suscipit quisquam doloribus eius.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt corrupti nemo, facere debitis laborum aut, inventore rerum veritatis incidunt tempore quasi officiis autem ad, doloremque temporibus ab nihil repellat? Tenetur.</p>
        <button><a href="#">LEARN MORE</a></button>
    </div>
    <div id="right-sec">
        <img src="../assets/img/graph-400x305.jpg" alt="graph">
    </div>
 </section>
</template>

 <script>
  export default{
    name:'TheFinantialSection'
  }
 </script>

 <style lang="scss">
   
    #container{
        display:flex;
        
          #left-sec{
            width: 50%;
            
            padding: 50px;
              button{
                background-color: #5ADDCD;
                border-color: #5ADDCD;
                border-radius: 20px;
                    }
              a{
                text-decoration: none;
                color: white;
               }
         }
         
    }
</style>