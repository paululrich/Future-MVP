<template>
  <div class="navbar">
      <h1 style="color:black; z-index: 1; flex-grow: 1;">Clients</h1>
      <span style="font-size:35px;cursor:pointer; padding-right: 30px;padding-top: 14px;" @click="openNav()">&#9776 </span>
    </div>

    <div id="mySidenav" class="sidenav">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav()">&times;</a>
      <a href="/">Home</a>
      <a href="/strategy">Strategy</a>
      <a style="color:#f1f1f1 !important;">Clients</a>
      <a href="/partner">Partner</a>
      <a href="/about_us">About us</a>
      <a href="/contact">Contact</a>
    </div>
    
    
<div style="width:100%; display:flex; flex-wrap: wrap; gap: 20px; margin-top: 90px;">
  <Spielerkarte
  bildUrl="https://a.espncdn.com/combiner/i?img=/i/headshots/nfl/players/full/3915511.png&w=350&h=254"
  name="Joe Burrow"
  teamPosition="Quarterback, Cincinnati Bengals"
  university="Louisianna State University"
  instagramLink="https://www.instagram.com/joeyb_9/"
/>
<Spielerkarte
  bildUrl="https://a.espncdn.com/combiner/i?img=/i/headshots/nfl/players/full/4038941.png&w=350&h=254"
  name="Justin Herbert"
  teamPosition="Quarterback, Los Angeles Chargers"
  university="University of Oregon"
  instagramLink="https://www.instagram.com/justinherbert/"
/>
<Spielerkarte
  bildUrl="https://a.espncdn.com/combiner/i?img=/i/headshots/nfl/players/full/3044859.png"
  name="Chris Jones"
  teamPosition="Defensive Tackle, Kansas City Chiefs"
  university="Bowling Green State University"
  instagramLink="https://www.instagram.com/stonecoldjones95/"
/>
<Spielerkarte
  bildUrl="https://a.espncdn.com/combiner/i?img=/i/headshots/nfl/players/full/4040605.png"
  name="Nick Bosa"
  teamPosition="Defensive End, San Francisco 49ers"
  university="Ohio State University"
  instagramLink="https://www.instagram.com/nbsmallerbear/?hl=de"
/>
<Spielerkarte
  bildUrl="https://a.espncdn.com/combiner/i?img=/i/headshots/nfl/players/full/4262921.png"
  name="Justin Jefferson"
  teamPosition="Wide Receiver, Minnesota Vikings"
  university="Louisiana State University"
  instagramLink="https://www.instagram.com/jjettas2/"
/>
<Spielerkarte
  bildUrl="https://a.espncdn.com/combiner/i?img=/i/headshots/nfl/players/full/3045373.png"
  name="Jalen Ramsey"
  teamPosition="Cornerback, Miami Dolphins"
  university="Florida State University"
  instagramLink="https://www.instagram.com/jalenramsey/"
/>
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




.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.title {
  color: grey;
  font-size: 18px;
}

button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
}

button:hover, a:hover {
  opacity: 0.7;
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
    