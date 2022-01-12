<template>
  <section>
      <div class="container">
          <div class="logo-box">
              <img src="../../assets/images/university_logo.png" alt="">
          </div>
          <ul>
              <li><a href="#">home</a></li>
              <li><a href="#">about</a></li>
              <li><a href="#">coursese <span>new</span></a></li>
              <li><a href="#">events</a></li>
              <li><a href="#">facilities</a></li>
              <li><a href="#">news</a></li>
              <li><a href="#">adminissions <span>applay</span></a></li>
          </ul>
      </div>
  </section>
</template>

<script>
export default {
    name: 'HeaderBottom'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';
section{
     background-color: white;

    .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 25px 0;
        font-size: 14px;

        li:first-child a {
            color: $first-color;
        } 
        li{
            display: inline-block;
            margin: 0 10px;
            
            a{
                text-transform: uppercase;
                color: black;
                span{
                    color: white;
                    background-color: $second-color;
                }
            }
        }
    }
}
</style>