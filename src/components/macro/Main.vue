<template>
    <main>
        <Hero/>
        <About/>
        <Facilities/>
    </main>
</template>

<script>
import Hero from '../sections/meinSection/Hero.vue'
import About from '../sections/meinSection/About.vue'
import Facilities from '../sections/meinSection/Facilities.vue'
export default {
    name: 'Main',
    components:{
        Hero,
        About,
        Facilities
    }
}
</script>

<style lang="scss" scoped>

</style>