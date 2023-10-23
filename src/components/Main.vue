<script>
  import SectionFeedback from './partials/SectionFeedback.vue';
  import SectionVideo from './partials/SectionVideo.vue';
  import SectionJumbo from './partials/SectionJumbo.vue';
  import SectionCards from './partials/SectionCards.vue';
  import SectionArticles from './partials/SectionArticles.vue';
  import SectionBuy from './partials/SectionBuy.vue';
  import SectionWhiteCards from './partials/SectionWhiteCards.vue';
  import SectionCrossfit from './partials/SectionCrossfit.vue';

  export default{
  name: 'Main',
  components:{
    SectionFeedback,
    SectionVideo,
    SectionJumbo,
    SectionCards,
    SectionArticles,
    SectionBuy,
    SectionWhiteCards,
    SectionCrossfit,
  }
}
</script>

<template>
  <SectionFeedback />
  <SectionVideo />
  <SectionJumbo />
  <SectionCards />
  <SectionArticles />
  <SectionBuy />
  <SectionWhiteCards />
  <SectionCrossfit />
</template>

<style lang="scss" scoped>
</style>