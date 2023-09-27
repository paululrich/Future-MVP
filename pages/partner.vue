<template>
  <div class="navbar">
      <h1 style="color:black; z-index: 1; flex-grow: 1;">Partner</h1>
      <span style="font-size:35px;cursor:pointer; padding-right: 30px;padding-top: 14px;" @click="openNav()">&#9776 </span>
    </div>
    <div id="mySidenav" class="sidenav">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav()">&times;</a>
      <a href="/">Home</a>
      <a href="/strategy">Strategy</a>
      <a href="/clients">Clients</a>
      <a style="color:#f1f1f1 !important;">Partner</a>
      <a href="/about_us">About us</a>
      <a href="/contact">Contact</a>
    </div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="https://www.nfl.com/">
      <img src="https://a.espncdn.com/combiner/i?img=/i/espn/misc_logos/500/nfl.png" alt="Cinque Terre" width="600" height="400">
    </a>
</div>
<div class="clearfix"></div>
</div>
<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="https://lsusports.net/">
      <img src="https://a.espncdn.com/combiner/i?img=/i/teamlogos/ncaa/500/99.png" alt="Cinque Terre" width="600" height="400">
    </a>
</div>
<div class="clearfix"></div>
</div>
<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="https://soonersports.com/">
      <img src="https://a.espncdn.com/combiner/i?img=/i/teamlogos/ncaa/500/201.png" alt="Cinque Terre" width="600" height="400">
    </a>
</div>
<div class="clearfix"></div>
</div>
<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="https://www.miamidolphins.com/">
      <img src="https://a.espncdn.com/i/teamlogos/nfl/500/mia.png" alt="Cinque Terre" width="600" height="400">
    </a>
</div>
<div class="clearfix"></div>
</div>
<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="https://www.philadelphiaeagles.com/">
      <img src="https://a.espncdn.com/combiner/i?img=/i/teamlogos/nfl/500/phi.png" alt="Cinque Terre" width="600" height="400">
    </a>
</div>
<div class="clearfix"></div>
</div>
<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="https://gofrogs.com/">
      <img src="https://a.espncdn.com/combiner/i?img=/i/teamlogos/ncaa/500/2628.png" alt="Cinque Terre" width="600" height="400">
    </a>
</div>
<div class="clearfix"></div>
</div>
    </template>
    
    
    <style>
    body {
      font-family: "Lato", sans-serif;
    }
    .navbar {
      display: flex;
      margin-top:-20px;
      overflow: hidden;
      background-color: #ebebeb;
      position: fixed;
      top: 0;
      width: 100%;
      box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2)
    }
    .sidenav {
      height: 100%;
      width: 0;
      position: fixed;
      z-index: 1;
      top: 0;
      right: 0;
      background-color: #111;
      overflow-x: hidden;
      transition: 0.5s;
      padding-top: 60px;
    }
    
    .sidenav a {
      padding: 8px 8px 8px 32px;
      text-decoration: none;
      font-size: 25px;
      color: #818181;
      display: block;
      transition: 0.3s;
    }
    
    .sidenav a:hover {
      color: #f1f1f1;
    }
    
    .sidenav .closebtn {
      position: absolute;
      top: 0;
      right: 200px;
      font-size: 36px;
      margin-left: 50px;
    }
    
    @media screen and (max-height: 450px) {
      .sidenav {padding-top: 15px;}
      .sidenav a {font-size: 18px;}
    }




    div.gallery {
  border: 1px solid #ccc;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2)
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
  
}

* {
  box-sizing: border-box;
  
  
}

.responsive {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
  padding-top: 100px;  
}

@media only screen and (max-width: 700px) {
  .responsive {
    width: 49.99999%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 500px) {
  .responsive {
    width: 100%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}
    </style>
    
    
    <script setup>
    function openNav() {
      document.getElementById("mySidenav").style.width = "250px";
    }
    
    function closeNav() {
      document.getElementById("mySidenav").style.width = "0";
    }
    </script>
    