<template>
  <div id="app"> 
  <div class="ui borderless main menu">
    <div class="ui text container">
      <router-link to="/" ><span class="item active">홈</span></router-link>
      <router-link to="/portfolio" ><span class="item">포트폴리오</span></router-link>
     </div>
  </div>
<router-view/>
</div>
</template>

<script>
$(document)
  .ready(function() {

    // fix main menu to page on passing
    $('.main.menu').visibility({
      type: 'fixed'
    })
    $('.overlay').visibility({
      type: 'fixed',
      offset: 80
    })

    // lazy load images
    $('.image').visibility({
      type: 'image',
      transition: 'vertical flip in',
      duration: 500
    })

    // show dropdown on hover
    $('.main.menu  .ui.dropdown').dropdown({
      on: 'hover'
    })

    $('.item').click( function() {
      // console.log(this)
      $('.item').removeClass('active')
      $(this).addClass('active')
    })
  })
</script>

  <style type="text/css">

  body {
    background-color: #FFFFFF;
  }
  .main.container {
    margin-top: 2em;
  }

  .main.menu {
    margin-top: 4em;
    border-radius: 0;
    border: none;
    box-shadow: none;
    transition:
      box-shadow 0.5s ease,
      padding 0.5s ease
    ;
  }
  .main.menu .item img.logo {
    margin-right: 1.5em;
  }

  .overlay {
    float: left;
    margin: 0em 3em 1em 0em;
  }
  .overlay .menu {
    position: relative;
    left: 0;
    transition: left 0.5s ease;
  }

  .main.menu.fixed {
    background-color: #FFFFFF;
    border: 1px solid #DDD;
    box-shadow: 0px 3px 5px rgba(0, 0, 0, 0.2);
  }
  .overlay.fixed .menu {
    left: 800px;
  }

  .text.container .left.floated.image {
    margin: 2em 2em 2em -4em;
  }
  .text.container .right.floated.image {
    margin: 2em -4em 2em 2em;
  }

  .ui.footer.segment {
    margin: 5em 0em 0em;
    padding: 5em 0em;
  }

  .active
  {
    cursor: pointer;
    background: rgba(0,0,0,.03);
    color: #59C5FF;
  }
  .ui.text.container
  {
    max-width: 1280px!important;
  }
 </style>
