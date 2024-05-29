<!-- JS -->
<script>
export default {
    name: 'Jumbotron',
    data() {
        return {
            jumbotron: 'sono il jumbotron :)',
        };
    },
}
</script>
<!-- HTML -->
<template>
    <div class="jumbotron">{{ jumbotron }}</div>
</template>
<!-- CSS -->
<style scoped>
.jumbotron {
    width: 100vh;
    height: 500px;
    margin: 0 auto;
    background-color:antiquewhite; 
    text-align: center;
}
</style>