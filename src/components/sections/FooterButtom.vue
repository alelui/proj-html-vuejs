<template>
  <section>
        <div class="copyright">
             <p>© Copyright 2012 - 2022 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>
        </div>
        <ul class="socialIcons">
            <li><a href=""><i class="fab fa-facebook-f"></i></a></li>
            <li><a href=""><i class="fab fa-twitter"></i></a></li>
            <li><a href=""><i class="fab fa-youtube"></i></a></li>
            <li><a href=""><i class="fab fa-instagram"></i></a></li>
        </ul>
  </section>
</template>

<script>
export default {
    name: 'FooterButtom'
}
</script>

<style lang="scss" scoped>
section{
    height: 100px;
    border-top: 1px solid gray ;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 35px;
    font-size: 12px;
    .socialIcons{
        display: flex;
        li{
            margin: 0 15px
        }
    }
}
</style>