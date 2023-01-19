<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  data(){
    return{
      
    }
  },
  components: {
    AppTitle,
    AppHero
}
}
</script>

<template>
  <AppTitle></AppTitle>
  <AppHero></AppHero>
</template>

<style scoped>
h1 {
  padding: 10px;
}
</style>
