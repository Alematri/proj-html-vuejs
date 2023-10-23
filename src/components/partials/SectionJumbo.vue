<script>
  export default{
  name: 'SectionJumbo'
}
</script>

<template>
  <section>
    <div class="container">
      <h4>Join our mailing list today</h4>
      <h1>Insider offers & flashsales in your inbox every week.</h1>
      <img src="../../assets/img/Others/ghirigoro.png">
      <div class="d-flex align-items-center">
        <input type="@" placeholder="Insert your email...">
        <button class="btn btn-primary" type="submit">Subscribe</button>
      </div>

      <h5>Curabitur non nulla sit amet nisl tempus convaliis quis ac lectus dolor sit amet.</h5>

    </div>
  </section>

</template>

<style lang="scss" scoped>

  @use '../../scss/partials/vars' as *;

  section{
    height: 675px;
    background: linear-gradient(to right, $black 45%, rgba(0, 0, 0, 0)) center / cover, url(../../assets/img/Others/banner1-2x.jpg);
    background-size: cover;
    margin-top: 100px;
    .container{
      height: 100%;
      padding-top: 130px;
      h4{
        color: $red;
      }
      h1{
        color: $white;
        margin-top: 33px;
        width: 50%;
      }
      img{
        width: 72px;
        margin-top: 33px;
        margin-bottom: 33px;
      }
      h5{
        color: $gray;
        margin-top: 33px
      }
      input{
        border-radius: 20px;
        padding: 11px;
        width: 500px;
        border: 0;
        margin-right: 30px;
      }
      button{
        border-radius: 20px;
        padding: 11px 74px;
        font-size: 13px;
      }
    }
  }

</style>