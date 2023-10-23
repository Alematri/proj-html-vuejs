<script>
  export default{
  name: 'SectionWhiteCards'
}
</script>

<template>
  <section>
    <div class="container">
      <div class="card-wrapper d-flex align-items-center justify-content-between">

        <div class="card d-flex flex-column align-items-center justify-content-around p-5">
          <img class="logo" src="../../assets/img/Others/sponsor-1-2x-200x103.png">
          <img class="ghirigoro py-3" src="../../assets/img/Others/ghirigoroblu.png">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos suscipit tempore nemo iure beatae.</p>
          <a href="#">Find a partner<i class="fa-solid fa-angle-right ms-2"></i></a>
        </div>

        <div class="card d-flex flex-column align-items-center justify-content-around p-5">
          <img class="logo" src="../../assets/img/Others/sponsor-1-2x-200x103.png">
          <img class="ghirigoro py-3" src="../../assets/img/Others/ghirigoroblu.png">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos suscipit tempore nemo iure beatae.</p>
          <a href="#">Find a partner<i class="fa-solid fa-angle-right ms-2"></i></a>
        </div>

        <div class="card d-flex flex-column align-items-center justify-content-around p-5">
          <img class="logo" src="../../assets/img/Others/sponsor-1-2x-200x103.png">
          <img class="ghirigoro py-3" src="../../assets/img/Others/ghirigoroblu.png">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos suscipit tempore nemo iure beatae.</p>
          <a href="#">Find a partner<i class="fa-solid fa-angle-right ms-2"></i></a>
        </div>

        <div class="card d-flex flex-column align-items-center justify-content-around p-5">
          <img class="logo" src="../../assets/img/Others/sponsor-1-2x-200x103.png">
          <img class="ghirigoro py-3" src="../../assets/img/Others/ghirigoroblu.png">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos suscipit tempore nemo iure beatae.</p>
          <a href="#">Find a partner<i class="fa-solid fa-angle-right ms-2"></i></a>
        </div>

      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>

  @use '../../scss/partials/vars' as *;

  section{
    margin: 150px 0;
    .container{
      height: 100%;
      .card-wrapper{
      height: 100%;
        .card{
          text-align: center;
          width: 25%;
          border: 0;
        }
        img.logo{
          width: 135px;
        }
        img.ghirigoro{
          width: 50px;
        }
        p{
          color: $gray;
        }
        a{
          color: $black;
          text-decoration: none;
        }
      }
    }
  }

</style>