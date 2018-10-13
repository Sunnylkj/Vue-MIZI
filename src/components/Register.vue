<template>
  <div>
    <app-showHeader></app-showHeader>
    <div class="content"></div>
  </div>
</template>

<script>
  import Header from './public/Header.vue'
  export default {
    name: 'Register',
    components:{
      'app-showHeader':Header,
    }
  }
</script>

<style lang="scss" scoped>
  .content{
    width: 80%;
    height: 700px;
    background-color: yellow;
  }
</style>

