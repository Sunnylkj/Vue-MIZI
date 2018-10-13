<template>
  <div id="header">
    <img src="../../assets/logo.png" style="width: 200px;height: 60px;margin-top:10px;float: left;line-height: 80px">
    <select class="form-control" id="sel1">
      <option value="吴中区" selected="selected">吴中区</option>
      <option value="吴江区">吴江区</option>
      <option value="吴中区">姑苏区</option>
      <option value="虎丘区">虎丘区</option>
    </select>
    <ul class="menu" >
      <li class="li"><a href="">首页</a></li>
      <li class="li"><a href="">兼职</a></li>
      <li class="garden li"><a href="">社区</a>
        <ul class="submenu">
          <li><a href="">问答</a></li>
          <li><a href="">动态</a></li>
        </ul>
      </li>
      <li class="li"><a href="">我要招聘</a></li>
      <li class="lr li"><a href="">登录&nbsp;&nbsp;</a><span>|</span><a href="">&nbsp;&nbsp;注册</a></li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: "Header"
  }
</script>

<style scoped>
  #header {
    color: #fff;
    margin-top: -50px;
    width: 100%;
    min-width: 1100px;
    height: 80px;
    background-color: #333;
  }
  ul {
    list-style: none;
    padding: 0;
    text-align: center;
  }
  .li {
    display: inline-block;
    margin: 0 20px;
    width: 90px;
    height: 80px;
    line-height: 80px;
    cursor: pointer;
    position: relative;
  }
  .li:hover a{
    color: #4376a1;
    cursor: pointer;
  }
  .lr{
    list-style: none;
    display: inline-block;
    margin: 0 60px;
    line-height: 80px;
    float: right;
  }
  .menu>li .submenu{
    border:1px solid #aaa;
    background: #bbb;
    position:absolute;
    top:69px;
    display:none;
  }
  .menu>li:hover .submenu{
    display: block;
  }
  .submenu li{
    width: 80px;
    height: 40px;
    text-align: center;
    line-height: 40px;
  }
  .submenu li:hover{
    cursor: pointer;
    background-color: #333;
  }
  a{
    text-decoration: none;
    color: #fff;
  }
  .form-control{
    float: left;
    margin: 25px  20px;
    width: 80px;
    height: 30px;
    background-color: #ddd;
  }
</style>
