<template>
    <header>
        <HeaderTop :socialIcons="social"/>
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
    },
    data(){
        return{
            social: [
                {
                    icon:'fab fa-facebook-f',
                    url:'#',
                },
                {
                    icon:'fab fa-instagram',
                    url:'#',
                },
                {
                    icon:'fab fa-youtube',
                    url:'#',
                },
                {
                    icon:'fab fa-twitter',
                    url:'#',
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
header{
    height: 200px;
}
</style>