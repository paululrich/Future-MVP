<template>
  <body>

    <meta name="viewport" content="width=device-width, initial-scale=1">

<div class="container">
  <a  href="https://www.nfl.com/news/chris-jones-new-one-year-deal-with-chiefs-worth-up-to-25-million-kansas-city-has"><img src="https://cdn.vox-cdn.com/thumbor/VjCJlATlrAAmC9ZPw_FF71bt_sc=/0x0:4966x3311/1200x800/filters:focal(2042x772:2836x1566)/cdn.vox-cdn.com/uploads/chorus_image/image/72485160/usa_today_16601357.0.jpg" alt="Chris Jones" class="image"></a>
  <div class="overlay">
    <div class="text">Chris Jones new one-year deal with Chiefs <br> worth up to $25 million. Sep 2023</div>
  </div>
  </div>
  
</body>
</template>

<script setup>

</script>

<style>
.container {
  position: relative;
  width: 50%;
}

.image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.container:hover .image {
  opacity: 0.3;
}

.container:hover .middle {
  opacity: 1;
}

.text {
  background-color: transparent;
  color: black;
  font-size: 16px;
  padding: 8px 32px;
}
</style>
