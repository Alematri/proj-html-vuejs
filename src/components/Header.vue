<script>
  import Nav from './partials/Nav.vue';
  import Jumbo from './partials/Jumbo.vue';

  export default{
  name: 'Header',
  components:{
    Nav,
    Jumbo,
  }
}
</script>

<template>
  <Nav />
  <Jumbo />
</template>

<style lang="scss" scoped>
</style>