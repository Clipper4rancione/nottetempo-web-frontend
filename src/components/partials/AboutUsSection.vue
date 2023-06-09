<script>
export default {
  name: "AboutUsSection",
};
</script>

<template>
  <section class="about_us w-100 p-3">
    <div class="container d-flex">
      <div class="row">
        <div class="col-6">
          <div class="logo_big">
            <img src="/LOGO_NT_BASE.png" alt="Nottetempo Logo" />
          </div>
        </div>
        <div class="col-6 text-black my-5">
          <div class="welcome_to my-3">
            <h1 class="about_title">BENVENUTO SUL NOTTETEMPO!</h1>
          </div>
          <div class="description_area">
            <p class="my-5">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam
              quasi molestiae, libero assumenda non delectus illum odit commodi
              enim, repellendus quos praesentium! Numquam exercitationem nihil
              maxime voluptas sed, consectetur neque.
            </p>
          </div>
          <div class="discord-btn btn">
            <a href=""
              ><i class="fa-brands fa-discord"></i> Entra nel nostro server
              Discord!</a
            >
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- <div class="waves down about_w">
    <svg
      class="wave-1hkxOo"
      version="1.1"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 1440 100"
      preserveAspectRatio="none"
    >
      <path
        class="wavePath-haxJK1 animationPaused-2hZ4IO"
        d="M826.337463,25.5396311 C670.970254,58.655965 603.696181,68.7870267 447.802481,35.1443383 C293.342778,1.81111414 137.33377,1.81111414 0,1.81111414 L0,150 L1920,150 L1920,1.81111414 C1739.53523,-16.6853983 1679.86404,73.1607868 1389.7826,37.4859505 C1099.70117,1.81111414 981.704672,-7.57670281 826.337463,25.5396311 Z"
        fill="currentColor"
      ></path>
    </svg>
  </div> -->
</template>



<style lang="scss" scoped>
.about_us {
  background-color: #dac700;

  .logo_big {
    width: 100%;

    img {
      vertical-align: middle;
      width: 65%;
    }
  }

  .about_title {
    font-size: 4rem;
  }
  .discord-btn {
    background-color: #7289da;
    color: #fff;
    padding: 0.7rem 1.5rem;
    border-radius: 17px;

    a:hover {
      color: white;
    }

    i {
      margin-right: 8px;
      vertical-align: middle;
    }
  }
}
.waves.down.about_w {
  color: #dac700;
}
</style>