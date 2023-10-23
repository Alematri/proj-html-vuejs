<script>
export default{
name: 'SectionCards'
}
</script>

<template>
  <section>
    <div class="container">
      <div class="card-wrapper d-flex align-items-center justify-content-between">

        <div class="card d-flex flex-column align-items-center justify-content-around p-5">
          <img src="../../assets/img/Others/smartwatch.png">
          <div class="div">
            <h3>Team training</h3>
            <h4>Find a partner</h4>
          </div>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid voluptatum eum expedita fugit dolor earum eligendi corporis reprehenderit perferendis ea?</p>
          <a href="#">Find a partner<i class="fa-solid fa-angle-right ms-2"></i></a>
        </div>

        <div class="card d-flex flex-column align-items-center justify-content-around p-5">
          <img src="../../assets/img/Others/smartwatch.png">
          <div class="div">
            <h3>Team training</h3>
            <h4>Find a partner</h4>
          </div>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid voluptatum eum expedita fugit dolor earum eligendi corporis reprehenderit perferendis ea?</p>
          <a href="#">Find a partner<i class="fa-solid fa-angle-right ms-2"></i></a>
        </div>

        <div class="card d-flex flex-column align-items-center justify-content-around p-5">
          <img src="../../assets/img/Others/smartwatch.png">
          <div class="div">
            <h3>Team training</h3>
            <h4>Find a partner</h4>
          </div>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid voluptatum eum expedita fugit dolor earum eligendi corporis reprehenderit perferendis ea?</p>
          <a href="#">Find a partner<i class="fa-solid fa-angle-right ms-2"></i></a>
        </div>

      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>

  @use '../../scss/partials/vars' as *;

  section{
    background-color: $black;
    height: 800px;
    .container{
      height: 100%;
      .card-wrapper{
      height: 100%;
        .card{
          text-align: center;
          height: 560px;
          width: 400px;
          border: 3px solid $blue;
          border-radius: 10px;
          background-color: $black;
        }
        h3{
          color: $white;
        }
        h4{
          color: $yellow;
        }
        p{
          color: $gray;
        }
        a{
          color: $white;
          text-decoration: none;
        }
      }
    }
  }

</style>