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
    <main class="container">
      <div class="searchbar-container">
          <SearchBar/>
      </div>
      <div class="card-container">
        <h2>Found 62 characters</h2>
      </div>
   </main>
</template>

<style lang="scss" scoped>
.searchbar-container{
   width: 25%;
   padding:20px;
}
 .card-container{
    background-color: #fff;
    padding: 5px;
    h2{
    background-color: $secondary-color;
  
    padding:10px
    }
 }

</style>