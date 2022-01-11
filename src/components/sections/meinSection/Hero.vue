<template>
  <section class="hero"> 
      <div class="hero-text">
        <h1>Inspiring Tomorrow Leaders</h1>
        <h3>The Future Belongos To Those Whoo See Possibilities Today</h3>
        <button>find a course</button>
        <button>apply now</button>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';
.hero{
    height: calc(100vh - 250px);
    background-image: url('../../../assets/images/home_main_slider_bg.jpg');
    background-position-y: center;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;

    h1{
        font-size: 50px;
        margin: 10px auto;
    }
    button{
        margin: 30px 15px;
        padding: 10px 15px;
        font-size: 12px;
        text-transform: uppercase;
        border: none;
        color: inherit;
        background-color: $first-color;
        cursor: pointer;
    }
    button:last-child{
        background-color: $second-color;
    }
}
</style>