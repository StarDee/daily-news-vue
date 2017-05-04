<template>
  <div>
    <div class="photo">
      <img src="http://ooeqdvvze.bkt.clouddn.com/star123.png" alt="">
    </div>
    <p class="name">StarDee</p>
    <ul>
      <li><a href="https://github.com/stardee/daily-news-vue">项目github地址</a></li>
      <li><a href="http://stardee.github.io/">我的博客地址</a></li>
    </ul>
  </div>
</template>S

<script>
</script>

<style scoped lang="scss" rel="stylesheet/scss">
  .photo{
    width: 80px;
    height: auto;
    margin: 0 auto;
    padding: 30px 0;
    img{
      width: 80px;
      height: 80px;
      border-radius: 50%;
    }
  }
  .name{
    width: 100px;
    margin: 0 auto 30px auto;
    padding-bottom: 2px;
    color: #999;
    font-size: 20px;
    text-align: center;
    border-bottom: 1px solid #4bb6ae;
  }
  ul{
    width: 150px;
    margin: 0 auto;
    font-size: 18px;
    text-align: center;
    border-top: 1px solid #b6b6b6;
    li{
      padding: 10px;
      border-bottom: 1px solid #b6b6b6;
      p{
        color: #999;
      }
      a{
        color: #2482ab;
      }
    }
  }
  .btn{
    margin: 50px auto 0 auto;
    width: 100px;
    height: 40px;
    border: 1px solid #999;
    border-radius: 10px;
    color: #b22323;
    font-size: 18px;
    text-align: center;
    line-height: 40px;
  }
</style>
