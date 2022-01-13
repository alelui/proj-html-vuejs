<template>
  <section id="footer-top">
      <div  class="footer-box">
        <h3>AVADA UNIVERSITY</h3>
        <div>
            <i class="fas fa-home"></i><span>Residential Location 9521 Broadsberry Avenue Paddington RC7 9ZA</span>
        </div>
        <p><i class="fas fa-phone"></i><span>1.800.458.556</span></p>
        <p><i class="fas fa-envelope"></i><span>info@your-domain.com</span></p>
        <div>
            <i class="far fa-clock"></i><span>Monday – Friday: 8:00 AM – 10:00 PM</span>
        </div>
      </div>
      <div  class="footer-box"></div>
      <div class="footer-box"></div>
      <div class="footer-box"></div>
      <div class="footer-box"></div>
  </section>
</template>

<script>
export default {
    name: 'FooterTop'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';
    #footer-top{
        height: 500px;
        width: 100%;
        display: flex;
        background-image: url('../../assets/images/university_ft_bg.png');
        background-size: cover;
        background-position: center;
        font-size: 13px;
        padding: 50px;
        .fa-home, .fa-clock, .fa-phone, .fa-envelope{
            margin-right: 10px;
        }
        div:nth-of-type(1){
            h3{
                margin-bottom: 25px;
            }
            div{
                display: flex;
                .fa-home, .fa-clock{
                    position: relative;
                    top: 8px;
                }
            }
        } 
        div:nth-of-type(2) {flex-grow: 1;}
        div:nth-of-type(3) {flex-grow: 1;}
        div:nth-of-type(4) {flex-grow: 1.3;}
        div:nth-of-type(5) {flex-grow: 1.8;}
        .footer-box{
            width: 20%;
            height: 100%;
            border: 1px solid black;
            padding: 10px;
            line-height: 30px;
            
        }
    }
</style>