<template>
  <section id="news">
      <div class="container">
        <div class="news-title">
            <img class="logo" src="../../../assets/images/page-logo-1.png" alt="">
            <h2>Inspired By Excellence & Innovation</h2>
            <p>We offere a wide range of hight quality of teaching and extra-curricula activities.</p>
            <hr>
            <div class="news-main">
                <div class="box-news">
                    <div class="box-news__boxImg">
                        <img src="../../../assets/images/news_single_post_header_1-400x222.jpg" alt="">
                    </div>
                    <div class="box-news__title">
                        <h2>What do successful grads think you should study?</h2>
                        <p>By <span>admin</span>|March 16th, 2016</p>
                    </div>
                    <div class="box-news__info">
                        <div>
                            <span>Read More></span>
                        </div>
                        <div>
                            <i class="far fa-comments"></i><span>0</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'News'
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';
#news{
    margin-bottom: 200px;
    background-color: $bg-color-one;
}
.news-title{
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
    .news-main{
        width: 100%;
        display: flex;
        text-align: left;
    .box-news{
        background-color: white;
        width: calc(100% / 3);
        margin: 60px 0 150px;
        &__boxImg img{
            width: 100%;
        }
    }
    }
}
</style>