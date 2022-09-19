<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      现货/ 合约  --> 历史回测  --> 量化策略 --> 历史收益<br>
      <a href="https://introducepage.pages.dev/" target="_blank" rel="noopener">原始链接地址</a>.
    </p>
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
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
