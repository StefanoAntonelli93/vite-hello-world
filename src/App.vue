<!-- JS -->
<script>
import Title from './components/AppTitle.vue';
import Jumbotron from './components/AppHero.vue';
export default {
  name: 'MyApp',
  data() {
    return {
      subtitle: 'Hello World',
    };
  },
  components: {
    Title,
    Jumbotron,
  },
};
</script>

<!-- HTML -->
<template>
  <main>
    <Title />
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