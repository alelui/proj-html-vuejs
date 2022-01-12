<template>
  <section id="facilities">
      <div class="container">
            <div class="f__world-class">
                <h2>world class facilities</h2>
                <span>Avada university is devoteted to excellence in teachin, in learning, reaserching, and developing leaders in differents disciplines who make a difference globally</span>
                <div class="f__world-class__main-text">
                    <p><i class="fas fa-globe"></i><strong>International Focus</strong> - our students come fromo across the globe</p>
                    <p><i class="fas fa-graduation-cap"></i><strong>Residential Coursese</strong> - we encourage learning and grown</p>
                    <p><i class="far fa-address-book"></i><strong>Popple not profits</strong> - education is a righht not a privilage</p>
                </div>
                <span>Avada university is devoteted to excellence in teachin, in learning, reaserching, and developing leaders in differents disciplines who make a difference globally</span>
                <p><strong></strong></p>
                <p><strong></strong></p>
            </div>
            <div class="f__values">
                <h2>our values</h2>
                <p><i class="fas fa-plus"></i> our mission</p>
                <p><i class="fas fa-plus"></i> our philosophy</p>
                <p><i class="fas fa-plus"></i> our commitment</p>
                <p><i class="fas fa-plus"></i> our promise</p>
                <p><i class="fas fa-plus"></i> our values</p>
            </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Facilities'
}
</script>

<style lang="scss" scoped>
#facilities{
    @import '../../../assets/style/partials/variables.scss';
    background-color: #f7f5f4;

    .container{
        display: flex;
        

        .f__world-class,
        .f__values{
            margin: 100px 0;
        }
        .f__world-class{
            width: 55%;
            line-height: 30px;
            h2{
                text-transform: uppercase;
            }
            span{
                display: inline-block;
                width: 90%;
                font-size: 12px;
                line-height: 25px;
            }
            &__main-text{
                margin: 30px 0;
            }
            .fa-globe, .fa-graduation-cap, .fa-address-book{
                color: $first-color;
                margin: 0 6px;
            }
        }

        .f__values{
            width: 45%;
            text-transform: uppercase;
            p{
              background-color: white;
              padding: 10px 20px;
              margin: 10px 0;
              color: $first-color;
              cursor: pointer;
              
              .fa-plus{
                  margin: 0 15px;
              }
            }
        }
    }
}
</style>