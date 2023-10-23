<script>
  export default{
  name: 'Footer'
}
</script>

<template>
  <footer>

    <div class="container">
      <div class="row">

        <div class="col col-sx d-flex flex-column align-items-center">
          <img class="mb-5" src="../assets/img/Others/logo-200x34.png">
          <p class="mb-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Inventore ducimus aut sed quaerat sequi laboriosam.</p>
          <div class="social d-flex">
            <a href="#"><i class="fa-brands fa-facebook-f mx-2"></i></a>
            <a href="#"><i class="fa-brands fa-twitter mx-2"></i></a>
            <a href="#"><i class="fa-brands fa-youtube mx-2"></i></a>
            <a href="#"><i class="fa-brands fa-instagram mx-2"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin-in mx-2"></i></a>
          </div>
        </div>

        <div class="col col-center d-flex flex-column">
          <p>RECENT POSTS</p>
          <a href="#"><p><i class="fa-solid fa-angle-right me-2"></i>The best protein shake</p></a>
          <a href="#"><p><i class="fa-solid fa-angle-right me-2"></i>Ultimate cardio workout</p></a>
          <a href="#"><p><i class="fa-solid fa-angle-right me-2"></i>New juices avaiable now</p></a>
          <a href="#"><p><i class="fa-solid fa-angle-right me-2"></i>Tips to find training partners</p></a>
          <a href="#"><p><i class="fa-solid fa-angle-right me-2"></i>20 best healty recipes</p></a>
        </div>

        <div class="col col-dx d-flex flex-column">
          <p>CONTACT INFORMATIONS</p>
          <p>4746 Tipple Road Michigan 48449</p>
          <p>Mobile: 1.800.000.000</p>
          <p>Email: info@your-company.com</p>
        </div>

      </div>
    </div>

    <hr>

    <div class="copyright py-3">
      <span>@Copyright 2012 - 2020 | Avada theme by </span>
      <span class="white">ThemeFusion </span>
      <span>| All right reserved | Powered by </span>
      <span class="white">WordPress</span>
    </div>

  </footer>
</template>

<style lang="scss" scoped>

  @use '../scss/partials/vars' as *;

  footer{
    background-color: $black;
    .container{
      padding: 140px 0;
      .row{

        .col.col-sx{
          padding: 0 50px;
          img{
            width: 220px;
          }
          p{
            text-align: center;
            color: $gray;
          }
          a{
            color: $red;
          }
        }
        .col.col-center{
          p{
            text-align: center;
            color: $white;
            margin-bottom: 25px;
          }
          a{
            text-decoration: none;
          }
        }
        .col.col-dx{
          text-align: center;
          p{
            color: $white;
            &:nth-child(2){
              color: $gray;
            }
            &:nth-child(3){
              margin-bottom: 0;
            }
          }
        }
      }

    }
    .copyright{
      text-align: center;
      span.white{
        color: $white;
      }
    }
  }
</style>