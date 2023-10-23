<script>
  import SectionFeedback from './partials/SectionFeedback.vue';
  import SectionVideo from './partials/SectionVideo.vue';
  import SectionJumbo from './partials/SectionJumbo.vue';
  import SectionCards from './partials/SectionCards.vue';

  export default{
  name: 'Main',
  components:{
    SectionFeedback,
    SectionVideo,
    SectionJumbo,
    SectionCards,
  }
}
</script>

<template>
  <SectionFeedback />
  <SectionVideo />
  <SectionJumbo />
  <SectionCards />
</template>

<style lang="scss" scoped>
</style>