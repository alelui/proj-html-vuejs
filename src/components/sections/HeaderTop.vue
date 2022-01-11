<template>
  <section>
    <div class="container">
        <ul>
          <li><a href="#"><i class="fas fa-phone"></i> 1.800.567.8910 <span>24hrs</span></a></li>
          <li><a href="#"><i class="fas fa-envelope"></i> Contac Us</a></li>
          <li><a href="#"><i class="fas fa-graduation-cap"></i> Alumni</a></li>
          <li><a href="#"><i class="fas fa-university"></i> campus</a></li>
        </ul>
        <ul > 
          <li v-for="(icon, index) in icons" :key="index">
            <a href="#">
              <i :class=icon></i>
            </a>
          </li>
        </ul>
    </div>
  </section>
</template>

<script>
export default {
    name: 'HeaderTop',
    data(){
      return{
        icons: [
          'fab fa-facebook-f',
          'fab fa-instagram',
          'fab fa-youtube',
          'fab fa-twitter',
        ],
      }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';
  section{
    background-color: $first-color;

    .container{
    font-size: 14px;
    height: 50px;
    display: flex;
    justify-content: space-around;
    align-items: center;

    ul{
      display: flex;
      justify-content: space-around;

      li{
        padding: 0 15px;
        a{
          color: white;

          span{
            font-size: 10px;
            padding: 3px;
            position: relative;
            top: -1px;
          }
        }
      }
    }
  }
  }
</style>