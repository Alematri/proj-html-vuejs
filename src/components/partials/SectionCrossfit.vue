<script>
  export default{
  name: 'SectionCrossfit'
}
</script>

<template>
  <section>
    <div class="container d-flex flex-column justify-content-center">
      <div class="fa-play-container">
        <i class="fa-solid fa-play"></i>
      </div>
      <h1>Crossfit workout of the day</h1>
      <h2>November 15th, 2019</h2>
      <a href="#">View all videos<i class="ms-2 fa-solid fa-arrow-right"></i></a>

    </div>
  </section>

</template>

<style lang="scss" scoped>

  @use '../../scss/partials/vars' as *;

  section{
    height: 675px;
    background: linear-gradient(to right, rgba(0, 0, 50, 0.7) 50%, rgba(50, 0, 0, 0.7)) center / cover, url(../../assets/img/Others/banner14-2x.jpg);
    background-size: cover;
    margin-top: 100px;
    .container{
      height: 100%;
      width: 50%;
      text-align: center;
      position: relative;
      .fa-play-container{
        transform: translatex(-50%);
        top: 25%;
        left: 50%;
      }
      h1{
        color: $white;
        width: 100%;
        font-size: 3.5rem;
      }
      h2{
        color: $yellow;
        margin-top: 33px;
      }
      a{
        margin-top: 20px;
        color: $white;
        text-decoration: none;
      }
    }
  }

</style>