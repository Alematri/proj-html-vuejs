<script>
  import SectionFeedback from './partials/SectionFeedback.vue';
  import SectionVideo from './partials/SectionVideo.vue';
  import SectionJumbo from './partials/SectionJumbo.vue';

  export default{
  name: 'Main',
  components:{
    SectionFeedback,
    SectionVideo,
    SectionJumbo
  }
}
</script>

<template>
  <SectionFeedback />
  <SectionVideo />
  <SectionJumbo />
</template>

<style lang="scss" scoped>
</style>