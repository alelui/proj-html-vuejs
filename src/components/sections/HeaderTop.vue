<template>
  <section>
    <div class="container">
        <ul>
          <li v-for="(contact, index) in contacts" :key="index">
            <a href="#">
              <i :class="contact.icon"></i>
              {{contact.text}}
              <span v-html="contact.label"></span>
              </a>
            </li>
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
        contacts: Array
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/partials/variables.scss';
section{
  background-color: $first-color;

  .container{
    font-size: 12px;
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
        ::v-deep .label{
          opacity: 0.5;
          background-color: black;
        }
      }
    }
  }
}
</style>