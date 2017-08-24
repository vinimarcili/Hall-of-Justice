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
  background: #000 url('./../assets/images/justice-league.jpg') center center no-repeat;
  figure{
    margin: 30px auto 0;
    max-width: 500px;
    width: 100%;
  }
  h1{
    font-size: 30px;
    color: #fff;
    font-family: Tahoma, Geneva, sans-serif;
  }
}
</style>
