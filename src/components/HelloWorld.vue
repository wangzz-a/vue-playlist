<template>
  <div class="hello">
    <h1>{{title}}</h1>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        title: '这是我的第一个脚手架项目'
      }
    }
  }
</script>

<!-- css 作用域，有scoped属性之后就只作用于当前页面 -->
<style scoped>
  h1 {
    color: #0f5;
  }
</style>
