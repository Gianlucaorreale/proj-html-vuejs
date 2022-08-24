<template>
  <section>
    <div class="feed-header">
        <h1>Client Feedback</h1>
    </div>
    <div class="feed-main">
        <div id="cards-container">
            <div class="card">
                <img src="../assets/img/client-logo-4.png" alt="event-elevate">
                <p>"Avada finance offers a fantastic service! It is so easy to use and the customer support is the best around.
                     This payment option is my numer one choice. I always recommend it."
                </p>
                
            </div>
            <div class="card">
                <img src="../assets/img/client-logo-1-1.png" alt="bonjour-cafe">
                <p>"Avada finance offers a fantastic service! It is so easy to use and the customer support is the best around.
                     This payment option is my numer one choice. I always recommend it."
                </p>
            </div>
            <div class="card">
                <img src="../assets/img/client-logo-2.png" alt="">
                <p>"Avada finance offers a fantastic service! It is so easy to use and the customer support is the best around.
                     This payment option is my numer one choice. I always recommend it."
                </p>
            </div>
            <div class="card">
                <img src="../assets/img/client-logo-3.png" alt="">
                <p>"Avada finance offers a fantastic service! It is so easy to use and the customer support is the best around.
                     This payment option is my numer one choice. I always recommend it."
                </p>
            </div>
        </div>
        <div id="cards-container">
            <div class="card">
                <p><strong>ANDRE MENDOZA</strong></p>
                <p>CREATIVE MARKET</p>
            </div>
            <div class="card">
                <p><strong>ANDRE MENDOZA</strong></p>
                <p>CREATIVE MARKET</p>
            </div>
            <div class="card">
                <p><strong>ANDRE MENDOZA</strong></p>
                <p>CREATIVE MARKET</p>
            </div>
            <div class="card">
                <p><strong>ANDRE MENDOZA</strong></p>
                <p>CREATIVE MARKET</p>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name:'TheFeedbackSection'
}

</script>


<style lang="scss">
  .feed-header{
    height: 200px;
    background-color: #F9F9F9;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  #cards-container{
    display: flex;
    .card{
    width: 25%;
    border: 1px solid lightgray;
    
    p{
        text-align: center;
    }
  }
  }
</style>