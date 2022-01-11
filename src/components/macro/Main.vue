<template>
    <main>
        <Hero/>
    </main>
</template>

<script>
import Hero from '../sections/meinSection/Hero.vue'
export default {
    name: 'Main',
    components:{
        Hero,
    }
}
</script>

<style lang="scss" scoped>
    h3{
        color: red;
    }
</style>