<script>
import { objectToString } from '@vue/shared';

    export default {
    name: "AppCard",
    props:{
        info: Object,
    }
   }
</script>

<template>
    <div class="text-center py-3">
    <h3>{{ info.nickname }}</h3>
    <h2>{{ info.status }}</h2>
    </div>
</template>

<style lang="scss">
img{
    width:100%
}
</style>