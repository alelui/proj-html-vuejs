<template>
  <section>
      <div class="container">
          <div class="logo-box">
              <img src="../../assets/images/university_logo.png" alt="">
          </div>
          <ul>
            <li v-for="(nav, index) in navMenu" :key="index">
                <a :href=nav.url>
                    {{nav.text}} 
                    <span v-html="nav.label"></span>
                </a>
            </li>
          </ul>
      </div>
  </section>
</template>

<script>
export default {
    name: 'HeaderBottom',
    props:{
        navMenu:Array
    }
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
                ::v-deep .label{
                    color: white;
                    background-color: $second-color;
                }
            }
        }
    }
}
</style>