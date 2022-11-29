<script>
    import axios from 'axios';
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
            console.log(resp)
        //   this.characters = resp.data.results;
         })
    }
   }
</script>

<template>
   <section class="container">
    <div class="row">
      <AppCard 
       v-for="character in characters"
       :info="character"
       class="col-auto"/> 
    </div>
   </section>
</template>

<style lang="scss">

</style>