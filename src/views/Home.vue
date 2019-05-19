<template>
  <div class="home-wrap">
      <div class="bg">
          <div class="title-box">
              <h1>Jina You<br>Portfolio</h1>
          </div>
      </div>
      <div class="myprofile">
        <img src="../img/02.jpg" alt="" class="myPic">
        <h2>저는 프론트 개발을 좋아하는 웹 개발자입니다 :)</h2><br>
        <span>안녕하세요. 저는 영등포에서 살고 있는 유지나입니다. 현재 성수에 있는 직장에서 7년째 근무하고 있습니다. 기술지원, QA, 프론트 개발을 담당하고 있습니다.</span>
      </div>
      <div class="bottom">
          <h3>Welcome to Jina You Portfolio :)</h3>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.myprofile
{
    margin: 16px auto;
    width: 800px;
    height: 300px;
}
h2
{
    display: inline-block;
}
.home-wrap
{
    position: relative;
    width: 100%;
    max-width: 100%;
    background-image: url('../img/bg.png');
    background-size: cover;
    background-position: center;  
    background-repeat: no-repeat;
    height: 386px;
    /* padding-top: 10px; */
}
.bg
{
    position: relative;
    background-color: #fff;
    opacity: 0.8;
    width: 100%;
    height: 386px;
    padding: 53px 0; 
}
.ui.menu
{
    margin: 0;
}
.main.menu {
    margin-top: 0px;
}
.ui.footer.segment {
    margin: 0;
}
.title-box
{
    position: relative;
    width:600px;
    height:280px;
    border: 8px solid #59C5FF;
    margin: 0 auto;
    text-align:center;
    padding: 92px 0;
}
h1
{
    font-size: 36px;
    color: #59C5FF;
}
.myPic
{
    width: 216px;
    height: auto;
}
.bottom
{
    width: 100%;
    height: 60px;
    background-color: #59C5FF;
    color: #fff;
    text-align: center;
    padding: 15px 0;
}

</style>
