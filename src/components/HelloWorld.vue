<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ol>
      <li>
        <a
          href="https://sudh-17.github.io/webpack-todomvc/dist/index.html"
          target="_blank"
          rel="noopener"
        >JavaScript原生版本(webpack 打包)</a>
      </li>
      <li>
        <a
          href="https://sudh-17.github.io/vue-antd-todomvc/dist/index.html#/home"
          target="_blank"
          rel="noopener"
        >基于vue框架的版本</a>
      </li>
      <li>
        <a
          href="https://sudh-17.github.io/ant-design-todomvc/dist/index.html#/home"
          target="_blank"
          rel="noopener"
        >基于vue + ant-design-vue框架的版本</a>
      </li>
      <li>
        <a
          href="https://github.com/sudh-17/todomvc-spring-boot"
          target="_blank"
          rel="noopener"
        >基于spring-boot的后台服务接口</a>
      </li>
    </ol>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ol {
  padding: 0;
  width: 458px;
  left: 50%;
  position: relative;
  margin-left: -225px;
  text-align: left;
  padding-left: 0;
}
li {
  margin: 0 20px;
}
a {
  color: #42b983;
  font-size: 25px;
}
</style>
