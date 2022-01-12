<template>
    <main>
        <Hero/>
        <About/>
        <Facilities/>
        <Events/>
        <News/>
    </main>
</template>

<script>
import Hero from '../sections/meinSection/Hero.vue'
import About from '../sections/meinSection/About.vue'
import Facilities from '../sections/meinSection/Facilities.vue'
import Events from '../sections/meinSection/Events.vue'
import News from '../sections/meinSection/News.vue'
export default {
    name: 'Main',
    components:{
        Hero,
        About,
        Facilities,
        Events,
        News,
    }
}
</script>

<style lang="scss" scoped>

</style>