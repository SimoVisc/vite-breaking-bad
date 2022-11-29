<script>
export default {
    name: "AppCard",
    props:{
        info: Object,
    }
}
</script>

<template>
    <div class=" container text-center py-3">
    <img class=" img-fluid" :src="info.img" :alt="info.name" />
    <h3>{{ info.name }}</h3>
    <h2>{{ info.status }}</h2>
    </div>
</template>

<style lang="scss">

</style>