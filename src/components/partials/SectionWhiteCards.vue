<script>
  import { SectionWhiteCardsData } from '../data/data';
  export default{
  name: 'SectionWhiteCards',
  data() {
    return {
      SectionWhiteCardsData,
    }
  }
};
</script>

<template>
  <section>
    <div class="container">

      <div class="card-wrapper d-flex align-items-center justify-content-between">

        <div class="card d-flex flex-column align-items-center justify-content-around p-5"
        v-for="(card, index) in SectionWhiteCardsData" :key="index">
          <img class="logo" :src="card.logo">
          <img class="ghirigoro py-3" src="../../assets/img/Others/ghirigoroblu.png">
          <p>{{card.paragraph}}</p>
          <a href="#">{{card.link}}<i class="fa-solid fa-angle-right ms-2"></i></a>
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