<template>
  <section id="events">
      <div class="event-box one">
          <div class="text-box">
              <h2>cousese</h2>
              <hr>
              <p>Viue More</p>
          </div>
      </div>
      <div class="event-box two">
        <div class="text-box">
              <h2>events</h2>
              <hr>
              <p>Viue More</p>
          </div>
      </div>
      <div class="event-box three">
        <div class="text-box">
              <h2>last news</h2>
              <hr>
              <p>Viue More</p>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Events'
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';
#events{
    width: 100%;
    display: flex;
    overflow: hidden;
    .event-box{
        width: calc(100% / 3);
        height: 500px;
        background-size: cover;
        transition: 1s;
        position: relative;
        cursor: pointer;
        .text-box{
            text-align: center;
            color: white;
            width: 50%;
            margin: 0 auto;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            h2{
                font-size: 33px;
                text-transform: uppercase;
            }
            hr{
                width: 20%;
                margin: 20px auto;
                color: $first-color;
            }
        }
    }
    .event-box:hover{
        background-size: cover;
        scale: 1.3;
    }
    .one{
        background-image: url('../../../assets/images/home_courses_section_bg.jpg');
    }
    .two{
        background-image: url('../../../assets/images/home_events_section_bg.jpg');
    }
    .three{
        background-image: url('../../../assets/images/home_latest_news_section_bg.jpg');
    }
}

</style>