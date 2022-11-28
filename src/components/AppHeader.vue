<script>
    import AppLogo from './AppLogo.vue';

    export default {
        name: "AppHeader",
        components:{
            AppLogo
        }
    }
</script>
 
<template>
  <header class="d-flex align-items-center my-3">
     <AppLogo/>
     <h1>Breaking Bad Api</h1>
  </header>
</template>

<style lang="scss" scoped>
 
</style>