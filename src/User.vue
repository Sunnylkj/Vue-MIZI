<template>
  <div>
    <app-showSidebar></app-showSidebar>
  </div>
</template>
<script>
  import Sidebar from './components/public/Sidebar.vue'
  export default {
    name: "User",
    components:{
      'app-showSidebar':Sidebar,
    },
    methods:{
data:{
}
    }
    }
</script>

<style scoped>

</style>
