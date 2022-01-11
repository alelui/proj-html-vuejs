<template>
    <header>
        <HeaderTop/>
        <HeaderBottom/>
    </header>
</template>

<script>
import HeaderTop from '../sections/HeaderTop.vue'
import HeaderBottom from '../sections/HeaderBottom.vue'
export default {
    name: 'Header',
    components:{
        HeaderTop,
        HeaderBottom
    }
}
</script>

<style lang="scss" scoped>

    h2{
        color: blue;
    }
</style>