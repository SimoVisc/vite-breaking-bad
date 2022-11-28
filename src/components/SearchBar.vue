<script>
    export default {
    name: "SearchBar",
   }
</script>

<template>
    <select class="form-select searchbar" aria-label="Default select example">
        <option selected>Select Category</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
    </select>
</template>

<style lang="scss">
.searchbar{
width: 200px;
}
</style>