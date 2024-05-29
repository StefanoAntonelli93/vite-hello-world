<!-- JS -->
<script>
export default {
    name: 'title',
    data() {
        return {
            title: 'La mia prima app con Vite!',
        };
    },
   
};
</script>


<!-- HTML -->
<template>
    <h1>{{ title }}</h1>
</template>


<!-- CSS -->
<!-- con SCOPED solo gli elementi che vivono dentro 'App' in questo caso verranno contaminati dal css -->
<!--  senza SCOPED se footer h2 diventa anche lui del colore qui sotto -->
<style scoped>
h1 {
    color: blueviolet;
}
</style>