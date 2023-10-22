<script>
  export default{
  name: 'SectionVideo'
}
</script>

<template>
  <section>

    <div class="div d-flex">

      <div class="video">
        <div class="fa-play-container">
          <i class="fa-solid fa-play"></i>
        </div>
      </div>

      <div class="info">
        <h3>Tune up your workouts</h3>
        <h1>The Best health & fitness advice online</h1>

        <div class="theme-fusion d-flex my-4 align-items-center">
          <img src="../../assets/img/Others/unnamed.jpg">
          <div class="div">
            <p>ThemeFusion</p>
            <img src="../../assets/img/Others/youtube999.png">
          </div>
        </div>

        <h4>Arcu eu facilisi u quisque placerat nunc habitant. Magna semper mauris, veneatis, leo integer sit pellentesque.</h4>

        <button class="btn btn-primary" type="submit"><i class="fa-brands fa-youtube me-2"></i>Visit my YouTube channel</button>
      
      </div>
    </div>

    <div class="container">
      <h3>Featured playlist</h3>
      <div class="card-container mt-5 d-flex justify-content-between">

        <div class="card"> <!-- //DINAMICIZZARE -->
          <div class="fa-play-container">
            <i class="fa-solid fa-play"></i>
          </div>
          <div class="card-info">
            <h4>Things & glute workout</h4> <!-- //DINAMICIZZARE -->
            <h6>Increase your mobility</h6> <!-- //DINAMICIZZARE -->
          </div>
        </div>

        <div class="card">
          <div class="fa-play-container">
            <i class="fa-solid fa-play"></i>
          </div>
          <div class="card-info">
            <h4>Things & glute workout</h4>
            <h6>Increase your mobility</h6>
          </div>
        </div>

        <div class="card">
          <div class="fa-play-container">
            <i class="fa-solid fa-play"></i>
          </div>
          <div class="card-info">
            <h4>Things & glute workout</h4>
            <h6>Increase your mobility</h6>
          </div>
        </div>
        
      </div>
    </div>

  </section>
</template>

<style lang="scss" scoped>

@use '../../scss/partials/vars' as *;

  section{
    height: 1615px;
    background-color: $white;
    .video{
      width: 50%;
      height: 865px;
      background: url(../../assets/img/Others/service15-2x.jpg); //DINAMICIZZARE
      background-size: cover;
      border: 0;
      border-bottom-right-radius: 40px;
      box-shadow: 10px 10px 10px rgba($color: $black, $alpha: .2);
      position: relative;
      bottom: 58px;
      .fa-play-container {
        top: 50%;
        right: 50%;
      }
    }
    .info{
      // margin-right:100px;
      width: 50%;
      padding: 100px;
      h3{
        color: $blue;
      }
      h1{
        font-size: 4rem;
      }
      .theme-fusion{
        p{
          margin: 0;
        }
      }
      button{
        border-radius: 20px;
        padding: 11px 34px;
        font-size: 13px;
        margin-top: 33px;
        margin-right: 15px;
        background-color: #e62117;
        border: 0;
      }
    }
    .container{
      .card-container{
        .card{
          height: 435px;
          width: 407px;
          border-bottom-right-radius: 40px;
          background: url(../../assets/img/Others/video2-2x.jpg);
          background-size: cover;
          border: 0;
          box-shadow: 10px 10px 10px rgba($color: $black, $alpha: .2);
          padding: 40px;
          .fa-play-container{
            top: 40%;
            right: 43%;
          }
          .card-info{
            text-align: center;
            position: relative;
            top: 430px;
            h6{
              color: $blue;
            }
          }
        }
      }
    }
  }
  
</style>