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
  <header>
     <AppLogo/>
     <h1>Breaking Bad Api</h1>
  </header>
</template>

<style lang="scss" scoped>
 header{
    display: flex;
    align-items: center;
 }
</style>