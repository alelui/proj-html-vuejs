<template>
  <section id="about">
      <div class="container">
        <div class="about-title">
            <img src="../../../assets/images/page-logo-1.png" alt="">
            <h2>Inspired By Excellence & Innovation</h2>
            <p>We offere a wide range of hight quality of teaching and extra-curricula activities.</p>
            <hr>
        </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';
.about-title{
    text-align: center;
    img{
        margin: 70px 0 30px;
    }
    p{
        color: #94979f;
        margin: 30px 0;
    }
    hr{
        width: 20%;
        margin: 0 auto;
        color: $first-color;
    }
    // background-color: $second-color;
}
</style>