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
          <img class="background" src="../../assets/img/Others/service6-2x.jpg">
          <div class="card-info d-flex flex-column justify-content-end">
            <img class="ghirigoro ms-5" src="../../assets/img/Others/ghirigorobianco.png">
            <h3 class="ms-5">Crossfit workout</h3> 
            <h6 class="ms-5 mb-5">Push your limits</h6>
          </div>
        </div>

        <div class="card"> <!-- //DINAMICIZZARE -->
          <img class="background" src="../../assets/img/Others/service6-2x.jpg">
          <div class="card-info d-flex flex-column justify-content-end">
            <img class="ghirigoro ms-5" src="../../assets/img/Others/ghirigorobianco.png">
            <h3 class="ms-5">Crossfit workout</h3> 
            <h6 class="ms-5 mb-5">Push your limits</h6>
          </div>
        </div>

        <div class="card"> <!-- //DINAMICIZZARE -->
          <img class="background" src="../../assets/img/Others/service6-2x.jpg">
          <div class="card-info d-flex flex-column justify-content-end">
            <img class="ghirigoro ms-5" src="../../assets/img/Others/ghirigorobianco.png">
            <h3 class="ms-5">Crossfit workout</h3> 
            <h6 class="ms-5 mb-5">Push your limits</h6>
          </div>
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
      position: relative;
      bottom: 80px;
      .card{
        height: 420px;
        width: 407px;
        border-bottom-right-radius: 40px;
        border: 0;
        box-shadow: 10px 10px 10px rgba($color: $black, $alpha: .2);

        img.background{
          position: absolute;
          object-fit: cover;
          width: 100%;
          height: 100%;
          border-bottom-right-radius: 40px;
        }
        .card-info{
          height: 100%;
          z-index: 2;
          background-image: linear-gradient(to top, $black, transparent);
          border-bottom-right-radius: 40px;
          img.ghirigoro{
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