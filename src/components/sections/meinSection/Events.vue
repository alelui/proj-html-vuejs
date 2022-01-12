<template>
  <sections id="events">
      <div class="event-box one"></div>
      <div class="event-box tow"></div>
      <div class="event-box three"></div>
  </sections>
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
    .event-box{
        width: calc(100% / 3);
        height: 500px;
    }
    .one{
        background-color: green;;
    }
    .two{
        background-color: white;
    }
    .three{
        background-color: red;
    }
}

</style>