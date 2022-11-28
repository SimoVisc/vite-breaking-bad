<script>
    export default {
    name: "AppMain",
   }
</script>

<template>
    <main class="container">
      <div>Select Category</div>
      <div class="card-container">
        <h2>Found 62 characters</h2>
      </div>
   </main>
</template>

<style lang="scss" scoped>
 .card-container{
    background-color: #fff;
    padding: 5px;
    h2{
    background-color: var(--secondary-color);
    color: #fff;
    padding:10px
    }
 }

</style>