<script>
import { SectionArticlesData } from '../data/data';
export default{
  name: 'SectionArticles',
  data() {
      return {
        SectionArticlesData,
      }
    }
  };
</script>

<template>

  <section>

    <div class="container">

      <div class="text-row d-flex justify-content-between align-items-center">
        <h3>Latest articles</h3>
        <a href="#"><span>Read all articles</span><i class="fa-solid fa-angle-right ms-2 me-5"></i></a>
      </div>

      <div class="card-container mt-5  d-flex justify-content-between">

        <div class="d-flex flex-column"
        v-for="(card, index) in SectionArticlesData" :key="index">
          <div class="card">
            <img :src="card.background">
          </div>
          
          <div class="card-info mt-4">
            <h4>{{ card.title }}</h4>
            <h6>{{ card.subtitle }}</h6>
          </div>
        </div>
        
      </div>

    </div>

  </section>

</template>


<style lang="scss" scoped>

@use '../../scss/partials/vars' as *;

section{
  .container{
    padding: 180px 0px;
    .text-row{
      a{
        text-decoration: none;
        color: $black;
      }
    }
      .card-container{
        .card{
          position: relative;
          height: 250px;
          width: 405px;
          border: 0;
          padding: 0px;
          box-shadow: 10px 10px 10px rgba($color: $black, $alpha: .2);
            img{
              object-fit: cover;
              width: 100%;
              height: 100%;
            }
          .fa-play-container{
            top: 40%;
            right: 43%;
          }
        }
        .card-info{
          margin-left: 25px;
          }
      }
    }
  }

</style>
