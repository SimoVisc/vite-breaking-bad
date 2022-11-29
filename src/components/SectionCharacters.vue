<script>
    import axios from "axios";
    import AppCard from './AppCard.vue';
    export default {
    name: "SectionCharacters",
    components: {
        AppCard
    },
    data(){
        return{
            characters:[]
        }
    },
    created(){
        axios.get("https://www.breakingbadapi.com/api/characters").then((resp)=>{
        this.characters === resp.data.result
        })
    }
   }
</script>

<template>
   <section class="container">
    <div class="row">
       <AppCard class="col-auto" />
    </div>
   </section>
</template>

<style lang="scss">

</style>