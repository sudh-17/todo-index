<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li><a href="https://sudh-17.github.io/webpack-todomvc/dist/index.html" target="_blank" rel="noopener">javascript原生版本(webpack 打包)</a></li>
      <li><a href="https://sudh-17.github.io/vue-antd-todomvc/dist/index.html#/home" target="_blank" rel="noopener">基于vue框架的版本</a></li>
      <li><a href="https://sudh-17.github.io/ant-design-todomvc/dist/index.html#/home" target="_blank" rel="noopener">基于vue + ant-design-vue框架的版本</a></li>
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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
  margin: 10px 0;
}
a {
  color: #42b983;
  font-size: 25px;
}
</style>
