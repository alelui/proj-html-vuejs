<template>
  <section id="about">
      <div class="container">
        <div class="about-title">
            <img class="logo" src="../../../assets/images/page-logo-1.png" alt="">
            <h2>Inspired By Excellence & Innovation</h2>
            <p>We offere a wide range of hight quality of teaching and extra-curricula activities.</p>
            <hr>
            <div class="about-main">
                <div class="about-main__text">
                    <h2>why chose avanda university</h2>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minima in odio, esse iste hic tenetur excepturi amet sit, eveniet accusamus iure commodi libero consequatur sed dolores ratione soluta odit eligendi!</p>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minima in odio, esse iste hic tenetur excepturi amet sit, eveniet accusamus iure commodi libero consequatur sed dolores ratione soluta odit eligendi!</p>                            

                </div>
                <div class="about-main__video">
                    <img src="../../../assets/images/business_seminar_event_feat-600x402.jpg" alt="">
                </div>
            </div>
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
    .logo{
        margin: 70px 0 30px;
    }
    p{
        color: $third-color;
        margin: 30px 0;
    }
    hr{
        width: 20%;
        margin: 0 auto;
        color: $first-color;
    }
    .about-main{
        width: 100%;
        display: flex;
        margin: 50px 0;

        &__text, &__video{
            width: 50%;
        }
        &__text{
            text-align: left;
            h2{
                text-transform: uppercase;
            }
            p{
                font-size: 14px;
            }
        }
        &__video img{
            width: 70%;
        }
    }
}
</style>