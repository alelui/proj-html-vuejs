<template>
    <footer>
        <FooterTop/>
        <FooterButtom/>
    </footer>
</template>

<script>
import FooterTop from '../sections/FooterTop.vue'
import FooterButtom from '../sections/FooterButtom.vue'
export default {
    name: 'Footer',
    components:{
        FooterTop,
        FooterButtom
    },
}

</script>

<style lang="scss" scoped>
</style>