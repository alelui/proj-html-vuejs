<template>
    <main>
        <Hero/>
        <About/>
    </main>
</template>

<script>
import Hero from '../sections/meinSection/Hero.vue'
import About from '../sections/meinSection/About.vue'
export default {
    name: 'Main',
    components:{
        Hero,
        About
    }
}
</script>

<style lang="scss" scoped>

</style>