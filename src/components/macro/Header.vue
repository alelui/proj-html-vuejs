<template>
    <header>
        <HeaderTop :socialIcons="social" :contacts="contacts"/>
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
            ],
            contacts: [
                {
                    url:'#',
                    icon:'fas fa-phone',
                    text:'1.800.567.8910',
                    label:'<span class="label">24hrs</span>'
                },
                {
                    url:'#',
                    icon:'fas fa-envelope',
                    text:'Contac Us'
                },
                {
                    url:'#',
                    icon:'fas fa-graduation-cap',
                    text:'Alumni'
                },
                {
                    url:'#',
                    icon:'fas fa-university',
                    text:'Campus'
                },
                
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
header{
    height: 200px;
}
</style>