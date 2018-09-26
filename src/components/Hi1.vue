<template>
  <div class="hello">
      {{msg1}}
  </div>
</template>

<script>
export default {
  name: 'Hi1',
  data () {
    return {
      msg1: 'Welcome to Hi11111.vue'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
