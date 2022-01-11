<template>
    <header>
        <HeaderTop/>
    </header>
</template>

<script>
import HeaderTop from '../sections/HeaderTop.vue'
export default {
    name: 'Header',
    components:{
        HeaderTop
    }
}
</script>

<style lang="scss" scoped>

    h2{
        color: blue;
    }
</style>