<!-- JS -->
<script>
import Title from './components/AppTitle.vue';
export default {
  name: 'MyApp',
  data() {
    return {
      subtitle: 'Hello World',
    };
  },
  components: {
    Title,
  },
};
</script>

<!-- HTML -->
<template>
  <main>
    <Title />
    <h2>{{ subtitle }}</h2>
  </main>
</template>

<!-- CSS -->

<style scoped>
h2 {
  color: chocolate;
}
</style>