<template>
  <div id="app">
    <div>页面测试3</div>
    <calculator></calculator>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'
export default {
  name: 'App',
  components: {
    "calculator":Calculator,
  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
  }
  #app{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #eee;
  }

</style>
