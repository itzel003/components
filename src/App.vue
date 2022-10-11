<template>
  <h1>Componentes</h1>
  <hr>
  <card url="https://cdn.svgporn.com/logos/vue.svg?response-content-disposition=attachment%3Bfilename%3Dvue.svg"
  nombre="Vue.js"/>
  <card url="https://cdn.svgporn.com/logos/vueuse.svg"
  nombre="VueUse"/>
  <card url="https://cdn.svgporn.com/logos/vuetifyjs.svg"
  nombre="Vuetity"/>
  <card url="https://cdn.svgporn.com/logos/angular-icon.svg"
    nombre="Angular"/>
    
  </template>
  <script>
    import Card from "./components/Card.vue";
    
    export default{
      components:{
    Card
},
    };
  </script>
  <style scoped>
   
  </style>