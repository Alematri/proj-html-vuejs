<script>
  export default{
  name: 'SectionVideo'
}
</script>

<template>
  <section>

    <div class="top-section d-flex">

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

    <div class="bottom-section container">

      <div class="text-row d-flex justify-content-between align-items-center">
        <h3>Featured playlist</h3>
        <a href="#"><span>View all video</span><i class="fa-solid fa-angle-right ms-2"></i></a>
      </div>


      <div class="card-container mt-5 d-flex justify-content-between">

        <div class="d-flex flex-column">
          <div class="card">
            <img src="../../assets/img/Others/video2-2x.jpg"> <!-- //DINAMICIZZARE -->
            <div class="fa-play-container">
              <i class="fa-solid fa-play"></i>
            </div>
          </div>
          
          <div class="card-info mt-4">
            <h4>Things & glute workout</h4>
            <h6>Increase your mobility</h6>
          </div>
        </div>
        
        <div class="d-flex flex-column">
          <div class="card">
            <img src="../../assets/img/Others/video2-2x.jpg">
            <div class="fa-play-container">
              <i class="fa-solid fa-play"></i>
            </div>
          </div>
          
          <div class="card-info mt-4">
            <h4>Things & glute workout</h4>
            <h6>Increase your mobility</h6>
          </div>
        </div>

        <div class="d-flex flex-column">
          <div class="card">
            <img src="../../assets/img/Others/video2-2x.jpg">
            <div class="fa-play-container">
              <i class="fa-solid fa-play"></i>
            </div>
          </div>
          
          <div class="card-info mt-4">
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
    height: 1520px;
    background-color: $white;
    .top-section{
      margin-bottom: 80px;
      .video{
        width: 50%;
        height: 865px;
        background: url(../../assets/img/Others/service15-2x.jpg);
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
    }

    .bottom-section{
      .text-row{
        a{
          text-decoration: none;
          color: $black;
        }
      }
      .card-container{
        .card{
          position: relative;
          height: 250px;
          width: 405px;
          border: 0;
          padding: 0px;
          box-shadow: 10px 10px 10px rgba($color: $black, $alpha: .2);
          border-bottom-right-radius: 40px;
            img{
              object-fit: cover;
              width: 100%;
              height: 100%;
              border-bottom-right-radius: 40px;
            }
          .fa-play-container{
            top: 40%;
            right: 43%;
          }
        }
        .card-info{
          text-align: center;
            h6{
              color: $blue;
            }
          }
      }
    }
  }
  
</style>