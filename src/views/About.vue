<template>
<div class="about">
  <h1>Jina You를 소개합니다</h1>
  <div class="ui grid">
     <!-- <div class="four wide column">
     <div class="ui vertical fluid menu">
        <a class="item active"> 
          누구세요
        </a>
        <a class="item">
          개발자 스펙
        </a>
        <a class="item">
          최근 경력
        </a>
      </div>
    </div> -->
    <div class="twelve wide stretched column">
      <div class="ui segment active">
        <div class="ui three column grid">
            <div class="column">
              <div class="ui fluid card">
                <div class="image">
                  <img src="../img/02.jpg" class="profile">
                </div>
                <div class="content">
                  <a class="header">Jina You</a>
                </div> 
              </div>
            </div>
            <div class="comment">
                <div>
                  <p>저는 웹 프론트엔드 개발자에요.</p>
                </div>
                <div>
                  <p>JS(ES5, ES6, ES7)와 Angular2, BackboneJS, Vue.js, CSS(& LESS)에 능숙해요.</p>
                </div>
                <div>
                  <p>최근에는 HTML5의 Audio, Canvas을 공부중이에요.</p>
                </div>
                <div>
                  <p>JS는 ES7과 ES8에 관심이 있구요, 프레임워크에는 Vue.js에 관심이 많아요.</p>
                </div>
                <div>
                  <p>Back 개발은 Spring, node.js를 사용해서 할 수 있어요.</p>
                </div>
                <div>
                  <p>그런데, 말 그대로 할 수만 있어요(...)</p>
                </div>
              </div>
        </div>
      </div>
      <div class="ui segment">
        <div><p>2그런데, 말 그대로 할 수만 있어요(...)</p></div>
      </div>
      <div class="ui segment">
        <div class="recent">
          <h2>위즈웨어</h2>
          <img src="../img/logo.gif" alt="" class="logo">
          <h4>근무기간 : 2012.11 ~</h4>
          <h4>주업무 : WebFront  </h4>     
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    $('.about .item')
      .tab();
  }
}
</script>

<style scoped>
.profile {
    background-position: center;
    width:300px;
}
.about {
    margin: 0 auto 1rem;
    width: 1254px;
    border: 0; 
}
h1
{
  margin: 10px 0;
  padding: 10px 300px;
}
.comment
{
  float:right;
  margin-top: 30px;
}
.ui.segment
{
  float: left;
}
.recent
{
  /* width: 300px;  */
  text-align: center;
  padding: 30px 0;
}
.logo
{
  width: 200px;
}
.ul .grid
{
  padding-left: 100px;
}
</style>