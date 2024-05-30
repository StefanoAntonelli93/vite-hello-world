<!-- JS -->
<script>
import AppTitle from './components/AppTitle.vue';
import Jumbotron from './components/AppHero.vue';
export default {
  name: 'MyApp',
  data() {
    return {
      subtitle: 'Hello World',
    };
  },
  components: {
    AppTitle,
    Jumbotron,
  },
};
</script>

<!-- HTML -->
<template>
  <main>
    <AppTitle />
    <h2>{{ subtitle }}</h2>
    <Jumbotron />
  </main>
</template>

<!-- CSS -->

<style scoped>
h2 {
  color: chocolate;
  text-align: center;
}
</style>