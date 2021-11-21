<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>Jenkins自动化部署测试</h1>
    <h1>当前时间：用来检测Jenkins的配置</h1>
    <img style="width: 100vw" src="../assets/auto.webp" alt="哇哈哈">
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string;
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
h1 {
  font-size: 24px;
  color: pink;
}
</style>
