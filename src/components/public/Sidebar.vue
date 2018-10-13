<template>
  <div id="user">
    <div id="dital">
      <ul>
        <li><a href="">个人资料</a></li>
        <li class="center"><a href="">修改资料</a></li>
        <li><a href="">兼职信息</a></li>
      </ul>
    </div>

  </div>

</template>

<script>
    export default {
        name: "Sidebar"
    }

</script>

<style scoped>
 a{
     text-decoration: none;
   color: #222;
   }
ul li{
  width:200px;
  height: 45px;
  line-height: 45px;
  font-size: 16px;
  text-align: center;
  list-style: none;
  background-color: #f0f0f0;
}
  .center{
    border-width: 1px 0;
    border-color: #8e8f90;
    border-style: solid;
  }

</style>
