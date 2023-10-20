<script>
  export default{
  name: 'SectionFeedback'
}
</script>

<template>
  <section>
    <div class="container">
      <div class="card-container d-flex">
        <div class="card">Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem, assumenda.</div>
        <div class="card">Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem, assumenda.</div>
        <div class="card">Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem, assumenda.</div>
      </div>
      <h1>"How you respond to the challenge in the second half will determine what you becaome after the game, whether you are a winner or a loser."</h1>
      <div class="img-container d-flex justify-content-center">
       <img src="../../assets/img/Others/ghirigoro.png" alt="">
      </div>
      <div class="author">
        foto Brad Johnson Las Vegas
      </div>
      
    </div>
  </section>
</template>

<style lang="scss" scoped>
  section{
    height: 1020px;
    width: 100%;
    background-color: red;
  }
    h1{
      text-align: center;
      color: white;
      width: 80%;
      margin: 510px auto 0px;
    }
    .img-container {
      img{
        width: 72px;
        margin: 30px auto;
    }
    }
    .author{
      text-align: center;
    }
</style>