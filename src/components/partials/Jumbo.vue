<script>
  export default{
  name: 'Jumbo'
}
</script>

<template>
  <div class="jumbo">
    <div class="container">
      <h4>Certified fitness professional</h4>
      <h1>Take control of your health</h1>
      <img src="../../assets/img/Others/ghirigoro.png">
      <h5>Curabitur non nulla sit amet nisl tempus convaliis quis ac lectus dolor sit amet.</h5>
      <button class="btn btn-primary" type="submit"><i class="fa-brands fa-youtube"></i><span class="ms-2">Visit my YouTube channel</span></button>
      <button type="button" class="btn btn-outline-dark"><span class="me-2">Buy Avada today</span><i class="fa-solid fa-arrow-right"></i></button>

      <div class="fa-play-container">
        <i class="fa-solid fa-play"></i>
      </div>

    </div>
  </div>

</template>

<style lang="scss" scoped>

  @use '../../scss/partials/vars' as *;

  .jumbo{
    height: 675px;
    width: 100%;
    background: linear-gradient(to right, $black 45%, rgba(0, 0, 0, 0)) center / cover, url(../../assets/img/Others/slider82x-scaled.jpg);
    background-size: cover;
    margin-top: 100px;
    .container{
      height: 100%;
      h4{
        color: $red;
        padding-top: 134px;
      }
      h1{
        color: $white;
        margin-top: 33px;
      }
      img{
        width: 72px;
        margin-top: 33px
      }
      h5{
        color: $gray;
        margin-top: 33px
      }
      button{
        border-radius: 20px;
        padding: 11px 34px;
        font-size: 13px;
        margin-top: 33px;
        margin-right: 15px;
      }
      button.btn-outline-dark{
        color: $white;
      }
      .fa-play-container {
        top: 40%;
        right: 24%;
      }
    }
  }

</style>