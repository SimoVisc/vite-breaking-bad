<script>
export default {
    name: "AppCard",
    props:{
        info: Object,
    }
}
</script>

<template>
    <div class="text-center py-3">
    <img class=" img-fluid" :src="info.image" :alt="info.name" />
    <h3>{{ info.name }}</h3>
    <h2>{{ info.status }}</h2>
    </div>
</template>

<style lang="scss">

</style>