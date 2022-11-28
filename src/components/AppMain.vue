<script>
    import SearchBar from './searchBar.vue';
    import SectionCharacters from './sectionCharacters.vue';
   
    export default {
    name: "AppMain",
    components: {
      SearchBar,
      SectionCharacters
    }
   }
</script>

<template>
    <main class="container ">
         <SearchBar/>
      <div class="card-container my-3 p-4">
        <h2 class="p-2">Found 62 characters</h2>
        <SectionCharacters/>
      </div>
   </main>
</template>

<style lang="scss" scoped>

 .card-container{
    background-color: #fff;
    padding: 5px;
    h2{
    background-color: $secondary-color;
    }
 }

</style>