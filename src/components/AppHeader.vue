<script>
export default {
  name: "AppHeader",
};
</script>

<template>
  <header>
  <div id="navbar" class="d-flex align-items-center justify-content-center p-2">
    <div class="logo_area">
      <img src="/LOGO_NT_BASE.png" alt="Logo Nottetempo" />
    </div>
  </div>
  <div id="nav_menu">
    <ul class="d-flex align-items-center justify-content-center p-2">
      <li><a href="#">Home</a></li>
      <li><a href="#">Canali</a></li>
      <li><a href="#">About Us</a></li>
      <li><a href="#">Contatti</a></li>
    </ul>
  </div>
</header>
</template>



<style lang="scss" scoped>
header{
  position: fixed;
  width: 100%;
  z-index: 999;
  #navbar {
  //NAVBAR GRADIENT COLOR
  background: #1b1b1b;
  background: -moz-linear-gradient(top, #1b1b1b 0%, #1b1b1b 50%, #131313 100%);
  background: -webkit-linear-gradient(
    top,
    #1b1b1b 0%,
    #1b1b1b 50%,
    #131313 100%
  );
  background: linear-gradient(to bottom, #1b1b1b 0%, #1b1b1b 50%, #131313 100%);
  ///////////////////////

  height: 60px;

  .logo_area {
    img {
      width: 55px;
      background-color: transparent;
    }
  }
}

#nav_menu {
  //background-color: #f2e00d;

  background: #000000;
  background: -moz-linear-gradient(top, #000000 0%, #f2e00d 45%, #f2e00d 100%);
  background: -webkit-linear-gradient(
    top,
    #000000 0%,
    #f2e00d 45%,
    #f2e00d 100%
  );
  background: linear-gradient(to bottom, #000000 0%, #f2e00d 45%, #f2e00d 100%);
  ul {
    list-style: none;

    li {
      padding-left: 20px;

      a {
        color: black;
      }
    }
  }
}
}

</style>