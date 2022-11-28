<script>
    import SearchBar from './searchBar.vue';
    export default {
    name: "AppMain",
    components: {
      SearchBar
    }
   }
</script>

<template>
    <main class="container ">
         <SearchBar/>
      <div class="card-container my-3">
        <h2>Found 62 characters</h2>
      </div>
   </main>
</template>

<style lang="scss" scoped>

 .card-container{
    background-color: #fff;
    padding: 5px;
    h2{
    background-color: $secondary-color;
  
    padding:10px
    }
 }

</style>