<template>
<div id="home">
  <app-showHeader></app-showHeader>
  <app-showHome1></app-showHome1>
</div>
</template>
<script>
  import Header from './public/Header.vue'
  import Search from './Home/Search.vue'
    export default {
      name: "Home",
      components:{
          'app-showHeader':Header,
          'app-showHome1':Search,
      }
    }
</script>

<style scoped>
#home{
  margin-top: 60px;
}
</style>
