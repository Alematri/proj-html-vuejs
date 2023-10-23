<script>
export default{
name: 'SectionCards',
  data() {
    return {
      cards: [
        {
          background: "/img/smartwatch.png",
          title: "Team training",
          subtitle: "Find a partner",
          paragraph: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nisi voluptatibus ut temporibus illum minus nihil atque dicta quam a iure?",
          link: "Find a partner"
        },
        {
          background: "/img/dumbell.png",
          title: "Crossfit workout",
          subtitle: "Push your limits",
          paragraph: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nisi voluptatibus ut temporibus illum minus nihil atque dicta quam a iure?",
          link: "Learn about Crossfit"
        },
        {
          background: "/img/body.png",
          title: "Weight loss plan",
          subtitle: "Shed those pounds",
          paragraph: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nisi voluptatibus ut temporibus illum minus nihil atque dicta quam a iure?",
          link: "Schedule a workout"
        },
      ],
    };
  },
};
</script>



<template>
  <section>
    <div class="container">
      <div class="card-wrapper d-flex align-items-center justify-content-between">

        <div class="card d-flex flex-column align-items-center justify-content-around p-5"
        v-for="(card, index) in cards" :key="index">
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