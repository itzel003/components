
<template>
    
    <grid>
        <img :src="url" alt="nombre">
        <h2 class="m-3">{{ nombre }}</h2>
        <a v-bind:href="url" target="_blank" class="m-2">Descargar</a>
    </grid>

</template>

<script>
    import Grid from "./Grid.vue";
    export default{
        Components:{
        Grid,
    },
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        }
    }
};
</script>


  <style scoped>
   div{
     display: inline-block;
     text-align: center;
     box-shadow: 0px 0px 15px rgb(0, 188, 94);
     padding: 1rem;
     border-end-start-radius: 10px;
     border-start-start-radius: 10px;
    }
    img{
        width: 8rem;
        padding: .5rem;
        background: snow;
        height: 8rem;
    }
    a{
        text-decoration: none;
        color:white;
        padding: .5rem;
        background-color: rgb(0, 76, 255);
        border-radius: 5px;   
    }
   </style>