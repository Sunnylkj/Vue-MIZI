<template>
  <div>
    <app-showSidebar></app-showSidebar>
    <div class="userDital">
    </div>
  </div>
</template>
<script>
  import Sidebar from './components/public/Sidebar.vue'
  export default {
      name: "userDital",
      components:{
        'app-showSidebar':Sidebar,
      }
    }
</script>
<style scoped>
  .userDital{
    width: 700px;
    height: 800px;
    background-color: yellow;
  }
</style>
