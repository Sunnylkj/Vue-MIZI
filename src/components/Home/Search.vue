<template>
  <div id="Home">
    <div class="search">
      <div class="content">
        <h2>米子兼职</h2><br><br>
        <h3>让你能开心赚钱的兼职网站</h3>
      </div>
     <div class="text">
       <form action="">
         <input class="kuang" type="text" placeholder="请输入您要查找的内容">
         <button class="button" type="submit">搜索</button>
       </form>
     </div>
    </div>
  </div>
</template>
<script>

    export default {
        name: "Search",
    }
</script>

<style scoped>
  *{padding: 0;
  margin: 0}
  .search{
    width: 100%;
    height: 450px;
    background-image:url('../../assets/Homeimage.jpg') ;
    background-repeat: no-repeat;
    background-size:100% 450px;
    position: absolute;
}
  .content{
    position: relative;
    font-size: 25px;
    color: #09f;
  }
  h2{
    float: left;
    left:100px;
    position: absolute;
  }
  h3{
    float: left;
    left:150px;
    position: absolute;
  }
  .text{
    position: absolute;
    top:450px;
    margin-top: -225px;
    left: 50%;
    margin-left: -200px;
  }
  .kuang{
    width: 300px;
    height: 50px;
    border: 3px solid #bfc2ca;
    border-radius: 5px;
  }
  .button{
    height: 55px;
    width: 100px;
    border: 3px solid #bfc2ca;
    border-radius: 5px;
  }
</style>
