<template>
  <div class="hello">
    <h2>{{ msg1 }}</h2>
    <h2>{{ msg2 }}</h2>
    <h2>{{ msg3 }}</h2>
    <h2><a href="#">Register</a></h2>

    <h2><a href="#">Login</a></h2>

  </div>
</template>

<script>
export default {
  name: 'index',
  data () {
    return {
      msg1: 'Shop for someone',
      msg2: 'or',
      msg3: 'Find a shopper from anywhere in the world'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
a {
  color: #42b983;
  text-decoration: none;
}
</style>
