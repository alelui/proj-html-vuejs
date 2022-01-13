<template>
  <section id="form">
      <div class="main-text">
            <h2>Joing Over<span> 500,000 Students </span>Enjoying Avada Education now</h2>
            <p>Become Part of Avada University to Further Your Career.</p>
      </div>
        <form action="">
            <input type="text" placeholder="Name">
            <input type="email" placeholder="Email">
            <input type="text" placeholder="Telephone">
            <button>applay</button>
        </form>
  </section>
</template>

<script>
export default {
    name: 'Form'
}
</script>

<style lang="scss" scoped>
@import '../../../assets/style/partials/variables.scss';
#form{
    background-color: #333c4e;
    color: white;
    text-align: center;
    padding: 70px 0;

    .main-text{
        span{
            color: $first-color;
        }
        p{
            color: #7c858e;
        }
    }

    form{
        margin-top: 30px;
        input{
            font-size: 18px;
            margin: 0 10px;
            padding: 10px;
            border: none;
            color: #a9adb7;
            background-color: #444d62;
        }
        button{
            font-size: 18px;
            width: 130px;
            padding: 10px;
            border: none;
            background-color: $first-color;
            color: white;
            text-transform: uppercase;
            cursor: pointer;
        }
    }
}
</style>