<script>
export default{
name: 'SectionBuy'
}
</script>

<template>
  <section>
    <div class="container">
      <h1>"I've failed over and over again in my life. And that is why I succeed"</h1>
      <img src="../../assets/img/Others/ghirigoro.png">
      <h5>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe quisquam autem temporibus similique architecto soluta maxime enim ipsa ratione totam. Minima error illo unde nostrum?</h5>
      <button class="btn btn-primary mt-5" type="submit">Buy Avada today<i class="fa-solid fa-angle-right ms-3"></i></button>

    </div>
  </section>

</template>

<style lang="scss" scoped>

  @use '../../scss/partials/vars' as *;

  section{
    height: 675px;
    background: linear-gradient(to top, $black 10%, rgba(0, 0, 0, 0)) center / cover, url(../../assets/img/Others/banner2-2x.jpg);
    background-size: cover;
    margin-top: 100px;
    .container{
      height: 100%;
      width: 50%;
      padding-top: 130px;
      text-align: center;
      h1{
        color: $white;
        margin-top: 33px;
        width: 100%;
        font-size: 3.5rem;
      }
      img{
        width: 72px;
        margin: 33px 0;
      }
      h5{
        color: $gray;
        margin-top: 33px
      }
      button{
        border-radius: 30px;
        padding: 11px 30px;
        font-size: 13px;
      }
    }
  }

</style>