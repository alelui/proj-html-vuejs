<template>
  <section>
    <div class="container">
        <ul>
          <li><a href="#"><i class="fas fa-phone"></i> 1.800.567.8910 <span>24hrs</span></a></li>
          <li><a href="#"><i class="fas fa-envelope"></i> Contac Us</a></li>
          <li><a href="#"><i class="fas fa-graduation-cap"></i> Alumni</a></li>
          <li><a href="#"><i class="fas fa-university"></i> Campus</a></li>
        </ul>
        <ul > 
          <li v-for="(icon, index) in socialIcons" :key="index">
            <a :href=icon.url>
              <i :class=icon.icon></i>
            </a>
          </li>
        </ul>
    </div>
  </section>
</template>

<script>
export default {
    name: 'HeaderTop',
    props: {
        socialIcons: Array,
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';
section{
  background-color: $first-color;

  .container{
    font-size: 12px;
    // height: 50px;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;

    ul:last-child{
      font-size: 20px;
    }

    li{
      padding: 0 15px;
      display: inline-block;
      a{
        color: white;
        span{
          opacity: 0.5;
          background-color: black;
        }
      }
    }
  }
}
</style>