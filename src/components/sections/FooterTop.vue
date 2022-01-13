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
      <div  class="footer-box">
            <h3>RECENT POSTS</h3>
            <div>
                <i class="fas fa-chevron-right"></i><span>What do successful grads think you should study?</span>
            </div>
            <hr>
            <div>
                <i class="fas fa-chevron-right"></i><span>Former student discusses success in the fashion industry</span>
            </div>
            <hr>
            <div>
                <i class="fas fa-chevron-right"></i><span>How do you best prepare for university?</span>
            </div>
            <hr>
      </div>
      <div class="footer-box">
        <h3>COURESE</h3>
        <ul>
            <li>Arts & Humanities</li>
            <li>Buoisness & Managment</li>
            <li>Engeniare & Tecnology</li>
            <li>Life Sience & Medicine</li>
            <li>Natura Sience</li>
        </ul>
        <h3>ADMISSION</h3>
        <ul>
            <li>Eligibility</li>
            <li>Application</li>
            <li>Review Proces</li>
            <li>How to play</li>
        </ul>
      </div>
      <div class="footer-box">
        <h3>Resources</h3>
        <ul>
            <li>Campus Directory</li>
            <li>Accademic calendar</li>
            <li>Spoprt Clubs</li>
            <li>Graduate Programs</li>
            <li>Faculty & Staff</li>
        </ul>
        <h3>QUICK LINKS</h3>
        <ul>
            <li>Universitary Library</li>
            <li>Campus Servise</li>
            <li>Carrresrs</li>
        </ul>
      </div>
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
        .fa-home, .fa-clock, .fa-phone, .fa-envelope, .fa-chevron-right{
            margin-right: 10px;
        }
        h3{
            margin: 20px 0;
        }

        div:nth-of-type(1){
            div{
                display: flex;
                .fa-home, .fa-clock{
                    position: relative;
                    top: 5px;
                }
            }
        }

        div:nth-of-type(2) {
            div{
                display: flex;
                    .fa-chevron-right{
                    position: relative;
                    top: 5px;
                }
            }
            hr{
            margin-bottom: 30px;
            }
        }
        div:nth-of-type(3) {flex-grow: 1;}
        div:nth-of-type(4) {flex-grow: 1.3;}
        div:nth-of-type(5) {flex-grow: 1.8;}
        .footer-box{
            width: 20%;
            height: 100%;
            border: 1px solid black;
            padding: 10px;
            line-height: 25px;
        }
    }
</style>