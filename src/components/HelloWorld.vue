<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

      <ul>
          <li><router-link to="/">home</router-link></li>
          <li><router-link to="/about">about</router-link></li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
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
