<script>
import AppTitle from './components/AppTitle.vue';
export default {
  data() {
    return {
      title: 'E funziona pure! Magico!',
    };
  },
  components:{
    AppTitle,
  }
};
</script>

<template>
  <AppTitle />
  <h2>{{ title }}</h2>
</template>

<style scoped>

</style>
