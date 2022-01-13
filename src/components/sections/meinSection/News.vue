<template>
  <section id="news">
      <div class="container">
        <div class="news-title">
            <img class="logo" src="../../../assets/images/page-logo-1.png" alt="">
            <h2>Today’s Univeristy News</h2>
            <p>Covering topics from classes to politics and student organization events.</p>
            <hr>
            <div class="news-main">
                <div class="box-news">
                    <div class="box-news__boxImg">
                        <img src="../../../assets/images/news_single_post_header_1-400x222.jpg" alt="">
                    </div>
                    <div class="box-news__title">
                        <h2>What do successful grads think you should study?</h2>
                        <p><span>By</span> admin <span>|March 16th, 2016</span></p>
                    </div>
                    <div class="box-news__info">
                        <div>
                            <span>Read More > </span>
                        </div>
                        <div>
                            <i class="far fa-comments"></i><span> 0</span>
                        </div>
                    </div>
                </div>
                <div class="box-news">
                    <div class="box-news__boxImg">
                        <img src="../../../assets/images/news_single_post_header_2-400x222.jpg" alt="">
                    </div>
                    <div class="box-news__title">
                        <h2>Former student discusses success in the fashion industry</h2>
                        <p><span>By</span> admin <span>|March 16th, 2016</span></p>
                    </div>
                    <div class="box-news__info">
                        <div>
                            <span>Read More > </span>
                        </div>
                        <div>
                            <i class="far fa-comments"></i><span> 0</span>
                        </div>
                    </div>
                </div>
                <div class="box-news">
                    <div class="box-news__boxImg">
                        <img src="../../../assets/images/news_single_post_header_3-400x222.jpg" alt="">
                    </div>
                    <div class="box-news__title">
                        <h2>How do you best prepare for university?</h2>
                        <p><span>By</span> admin <span>|March 16th, 2016</span></p>
                    </div>
                    <div class="box-news__info">
                        <div>
                            <span>Read More > </span>
                        </div>
                        <div>
                            <i class="far fa-comments"></i><span> 0</span>
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
            width: calc(100% / 3 - 20px);
            margin: 60px 10px 150px;
            color: $first-color;

            &__title,&__info{
                padding: 10px;
            }

            &__boxImg img{
                width: 100%;
            }
            &__title{
                h2{
                    margin: 20px 0;
                    font-size: 20px;
                }
                p{
                    margin: 0 0 30px;
                    color: $first-color;
                    span{
                        color: black;
                    }
                }
            }
            &__info{
                display: flex;
                justify-content: space-between;
                position: relative;
            }
        }
    }
}
</style>