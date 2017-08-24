<template>
  <div class="welcome">
    <figure>
      <img class="img-responsive" src="./../assets/images/hall-of-justice.jpg" alt="Hall of Justice" title="Hall of Justice">
    </figure>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'welcome',
  data () {
    return {
      msg: 'Welcome to Hall of Justice'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.welcome{
  padding: 15px;
  min-height: 100vh;
  width: 100%;
  background: url('./../assets/images/justice-league.jpg');
  figure{
    margin: 0 auto;
    max-width: 500px;
    width: 100%;
    img{
      opacity: 0;
    }
  }
  h1{

    text-transform: uppercase;
  }
}
</style>
