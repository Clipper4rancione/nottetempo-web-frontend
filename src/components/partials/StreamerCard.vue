<script>
export default {
  name: "StreamerCard",
};
</script>

<template>
  <div class="card-streamer">
    <div class="card">
      <b></b>
      <div class="content text-center">
        <p class="title">Some Fomous<br /><span>Creative Designer</span></p>
        <ul class="sci">
          <li>
            <a href="#">
              <i class="fa-brands fa-instagram"></i>
            </a>
          </li>

          <li>
            <a href="#"><i class="fa-brands fa-youtube"></i></a>
          </li>
          <li>
            <a href="#"><i class="fa-brands fa-twitch"></i></a>
          </li>

          <li>
            <a href="#">
              <i class="fa-brands fa-tiktok"></i>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>



<style lang="scss" scoped>
.card-streamer {
  //background-color: blue;
  height: 420px;
  width: 300px;
}
.card {
  position: relative;
  width: 280px;
  height: 400px;
  background: #f3e00c;
  display: flex;
  justify-content: center;
  align-items: center;
}

.card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(315deg, #f3e00c #c8ba03);
}

.card::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(315deg, #867400, #867400);
  filter: blur(30px);
}

.card b {
  position: absolute;
  inset: 6px;
  background: rgba(0, 0, 0, 0.6);
  z-index: 2;
}

.card img {
  position: absolute;
  z-index: 3;
  scale: 0.8;
  opacity: 0.25;
  transition: 0.5s;
}

.card:hover img {
  scale: 0.5;
  opacity: 0.9;
  transform: translateY(-70px);
}

.card .content {
  position: absolute;
  z-index: 3;
  bottom: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  transform: scale(0);
  transition: 0.5s;
}

.card:hover .content {
  transform: scale(1);
  bottom: 25px;
}

.content .title {
  position: relative;
  color: #121111;
  font-weight: 800;
  line-height: 1em;
  font-size: 1em;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  text-align: center;
}

.content .title span {
  font-weight: 300;
  font-size: 0.7em;
}

.content .sci {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 12px;
  margin-top: 5px;
  padding-left: 0rem;
}

.sci li {
  list-style: none;
  text-align: center;
  vertical-align: center;
}

.sci li a {
  position: relative;
  text-decoration: none;
  color: rgba(255, 255, 255, 0.5);
  background: rgba(0, 0, 0, 0.2);
  fill: currentColor;
  width: 30px;
  height: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 4px;
  transition: 0.5s;
  text-align: center;
}

.sci li a:hover {
  fill: currentColor;
  color: rgba(255, 255, 255, 1);
}
</style>