<template>
  <div id="app">
    <app-showHeader></app-showHeader>
    <div class="content">
    </div>
  </div>
</template>

<script>
  import Header from './public/Header.vue'

  export default {
    name: 'Login',
    components: {
      'app-showHeader': Header,

    }
  }
</script>

<style lang="scss" scoped>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }

  .content {
    width: 90%;
    height: 500px;
    background-color: pink;
    position: absolute;
    float: left;
    margin-left: 5%;
  }
</style>

