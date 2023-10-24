<script>
import { SectionCardsData } from '../data/data';
export default{
name: 'SectionCards',
  data() {
    return {
      SectionCardsData,
    }
  }
};
</script>



<template>
  <section>
    <div class="container">
      <div class="card-wrapper d-flex align-items-center justify-content-between">

        <div class="card d-flex flex-column align-items-center justify-content-around p-5"
        v-for="(card, index) in SectionCardsData" :key="index">
          <img :src="card.background">
          <div class="div">
            <h3>{{card.title}}</h3>
            <h4>{{card.subtitle}}</h4>
          </div>
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
          &:hover{
          transform: scale(1.05);
          transition: transform 0.2s ease-in-out;
      }
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