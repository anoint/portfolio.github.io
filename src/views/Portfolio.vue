<template>
  <div class="portFolio">
    <div class="ui special cards">
      <div class="card">
        <div class="blurring dimmable image">
          <div class="ui dimmer">
            <div class="content">
              <div class="center">
                <div class="ui inverted button">Add Friend</div>
              </div>
            </div>
          </div>
          <img class="ui image centered middle aligned" src="../img/2-01.png">
        </div>
        <div class="content">
          <a class="header">기술 스펙: html, css, js, jquery, oracle</a>
          <div class="meta">
            <span class="date">기간: 2019.02 ~ 2019.05</span>
          </div>
        </div>
        <div class="extra content">
          <a>
            <i class="users icon"></i>
            고객의 요청을 접수하고 프로세스화로 관리하는 시스템입니다.
          </a>
        </div>
      </div>
      <div class="card">
        <div class="blurring dimmable image">
          <div class="ui inverted dimmer">
            <div class="content">
              <div class="center">
                <div class="ui primary button">Add Friend</div>
              </div>
            </div>
          </div>
          <img class="ui image centered middle aligned" src="../img/2-02.png">
        </div>
        <div class="content">
          <a class="header">기술 스펙: html, css, js, jquery, oracle</a>
          <div class="meta">
            <span class="date">기간: 2019.02 ~ 2019.01</span>
          </div>
        </div>
        <div class="extra content">
          <a>
            <i class="users icon"></i>
            중국 식품 약품 규제를 하기 위한 접수시스템입니다.
          </a>
        </div>
      </div>
      <div class="card">
        <div class="blurring dimmable image">
          <div class="ui inverted dimmer">
            <div class="content">
              <div class="center">
                <div class="ui primary button">Add Friend</div>
              </div>
            </div>
          </div>
          <img class="ui image centered middle aligned" src="../img/2-03.png">
        </div>
        <div class="content">
          <a class="header">기술 스펙: html, css, js, jquery, oracle</a>
          <div class="meta">
            <span class="date">기간: 2018.02 ~ 2018.05</span>
          </div>
        </div>
        <div class="extra content">
          <a>
            <i class="users icon"></i>
            원가 예측 관리 시스템입니다.
          </a>
        </div>
      </div>
      <div class="card">
        <div class="blurring dimmable image">
          <div class="ui inverted dimmer">
           <div class="content">
              <a class="header">기술 스펙: html, css, js, jquery, oracle</a>
              <div class="meta">
                <span class="date">기간: 2018.02 ~ 2018.05</span>
              </div>
            </div>  
          </div>
          <img class="ui image centered middle aligned" src="../img/logo.gif">
        </div>
        <div class="content">
          <a class="header">기술 스펙: html, css, js, jquery, oracle</a>
          <div class="meta">
            <span class="date">기간: 2018.02 ~ 2018.05</span>
          </div>
        </div>
        <div class="extra content">
          <a>
            <i class="users icon"></i>
             UI 툴의 그룹 컴포넌트를 개발했습니다
          </a>
        </div>
      </div>
      <div class="card">
        <div class="blurring dimmable image">
          <div class="ui inverted dimmer">
            <div class="content">
              <div class="center">
                <div class="ui primary button">Add Friend</div>
              </div>
            </div>
          </div>
          <img class="ui image centered middle aligned" src="../img/2-04.png">
        </div>
        <div class="content">
          <a class="header">기술 스펙: html, css, js, jquery, oracle</a>
          <div class="meta">
            <span class="date">기간: 2018.02 ~ 2018.05</span>
          </div>
        </div>
        <div class="extra content">
          <a>
            <i class="users icon"></i>
            물질정보관리시스템입니다.
          </a>
        </div>
      </div>
    </div>
    <!-- <h1>This is an about page</h1> -->
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
  .portFolio
  {
      margin: 0 auto 1rem;
      width: 1254px;
      border: 0; 
  }
 .ui.card>.image, .ui.cards>.card>.image
  {
    background: #fff;
    height: 300px; 
  }
  .ui.card>.image:not(.ui)>img, .ui.cards>.card>.image:not(.ui)>img
  { 
    height: 220px;
    width: auto;
    padding-top:80px;
  }
  .ui.cards
  {
    margin-top: 20px;
  }
  #app > div.portFolio > div > div:nth-child(5) > div.blurring.dimmable.image > img
  {
    padding-top: 120px;
    height: 186px;
    width: auto;
    text-align: center;
  }  
  #app > div.portFolio > div > div:nth-child(3) > div.blurring.dimmable.image > img
  {
    width: 289px;
    height: auto;
    padding-left: 30px;
    padding-right: 30px;
    padding-top: 120px;
  }
#app > div.portFolio > div > div:nth-child(4) > div.blurring.dimmable.image > img
  {
    width: 302px;
    height: auto;
    padding-left: 30px;
    padding-right: 30px;
    padding-top: 114px;
  }

</style>


