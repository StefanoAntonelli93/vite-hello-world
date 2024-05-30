<!-- JS -->
<script>
export default {
    name: 'Title',
    data() {
        return {
            Title: 'La mia prima app con Vite!',
        };
    },
   
};
</script>


<!-- HTML -->
<template>
    <h1>{{ Title }}</h1>
</template>


<!-- CSS -->
<!-- con SCOPED solo gli elementi che vivono dentro 'App' in questo caso verranno contaminati dal css -->
<!--  senza SCOPED se footer h2 diventa anche lui del colore qui sotto -->
<style scoped>
h1 {
    color: blueviolet;
    text-align: center;
}
</style>