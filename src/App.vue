<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components:{
    AppTitle,
    AppHero
  }
}
</script>

<template lang="">
  <div>
    <AppTitle />
    <AppHero />
  </div>
</template>

<style scoped>
  *{
    font-family: Arial, Helvetica, sans-serif;
  }
</style>