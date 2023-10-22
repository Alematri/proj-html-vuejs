<script>
  export default{
  name: 'SectionFeedback'
}
</script>

<template>
  <section>
    <div class="container">
      <div class="card-container d-flex justify-content-between">
        <div class="card"> <!-- //DINAMICIZZARE -->
          <img src="../../assets/img/Others/ghirigorobianco.png">
          <h3>Crossfit workout</h3> 
          <h6>Push your limits</h6>
        </div>
        <div class="card">
          <img src="../../assets/img/Others/ghirigorobianco.png">
          <h3>Crossfit workout</h3>
          <h6>Push your limits</h6>
        </div>
        <div class="card">
          <img src="../../assets/img/Others/ghirigorobianco.png">
          <h3>Crossfit workout</h3>
          <h6>Push your limits</h6>
        </div>
      </div>
      <h1>"How you respond to the challenge in the second half will determine what you becaome after the game, whether you are a winner or a loser."</h1>
      <div class="img-container d-flex justify-content-center">
       <img src="../../assets/img/Others/ghirigoro.png">
      </div>
      <div class="author">
        <img src="../../assets/img/Others/avatar-1-2x.jpg" alt="Brad Johnson">
        <h5 class="mx-3">Brad Johnson</h5><span>Las Vegas</span>
      </div>
      
    </div>
  </section>
</template>

<style lang="scss" scoped>

  @use '../../scss/partials/vars' as *;

  section{
    height: 1020px;
    width: 100%;
    background-image: linear-gradient(to bottom right, blue, red);
  }
    .card-container{
      min-height: 300px;
      position: relative;
      bottom: 80px;
      .card{
        height: 435px;
        width: 407px;
        border-bottom-right-radius: 40px;
        background: linear-gradient(to top, rgba(0, 0, 0, 0.8) 35%, rgba(0, 0, 0, 0)) center center / cover, url(../../assets/img/Others/service6-2x.jpg); //DYNAMICIZZARE
        background-size: cover;
        border: 0;
        box-shadow: 10px 10px 10px rgba($color: $black, $alpha: .2);
        padding: 40px;
        img{
          margin-top: 260px;
          width: 40px;
        }
        h3{
          color: $white;
          margin-top: 25px;
        }
        h6{
          color: $yellow;
        }
      }
    }
    h1{
      text-align: center;
      color: white;
      width: 80%;
      margin: 0px auto;
      padding-top: 140px;
    }
    .img-container {
      img{
        width: 72px;
        margin: 30px auto;
    }
    }
    .author{
      text-align: center;
      img{
        height: 50px;
        border-radius: 50%;
      }
      h5{
        display: inline-block;
        color: $white;
      }
      span{
        color: white;
      }
    }
</style>