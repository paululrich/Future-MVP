<template>

    <div id="mySidenav" class="sidenav">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav()">&times;</a>
      <a href="/">Home</a>
      <a href="/strategy">Strategy</a>
      <a style="color:#f1f1f1 !important;">Clients</a>
      <a href="/partner">Partner</a>
      <a href="/about_us">About us</a>
      <a href="/contact">Contact</a>
    </div>
    
    <span style="font-size:35px;cursor:pointer;float:right" @click="openNav()">&#9776 </span>
<div style="width:100%; display:flex; flex-wrap: wrap; gap: 20px;">
  
<Spielerkarte
  bildUrl="https://static.clubs.nfl.com/image/private/t_editorial_landscape_12_desktop/bengals/wywob8gosfpknw5jsmdp"
  name="Joe Burrow"
  teamPosition="Quarterback, Cincinnati Bengals"
  university="Louisianna State University"
  instagramLink="https://www.instagram.com/joeyb_9/"
/>
<Spielerkarte
  bildUrl="https://a.espncdn.com/combiner/i?img=/i/headshots/nfl/players/full/4038941.png&w=350&h=254"
  name="Justin Herbert"
  teamPosition="test"
  university="test"
  instagramLink="test"
/>
<Spielerkarte
  bildUrl="https://img.donaukurier.de/ezplatform/images/_aliases/detail_teaser_item_image_variation/0/8/7/1/24351780-1-ger-DE/4363404_normal_RC2nMMUfcQ.jpg"
  name="Jusuf Elshani"
  teamPosition="test"
  university="test"
  instagramLink="test"
/>
<Spielerkarte
  bildUrl="https://static.clubs.nfl.com/image/private/t_editorial_landscape_12_desktop/bengals/wywob8gosfpknw5jsmdp"
  name="test"
  teamPosition="test"
  university="test"
  instagramLink="test"
/>
<Spielerkarte
  bildUrl="https://static.clubs.nfl.com/image/private/t_editorial_landscape_12_desktop/bengals/wywob8gosfpknw5jsmdp"
  name="test"
  teamPosition="test"
  university="test"
  instagramLink="test"
/>
</div>    
    </template>
    
    
<style>
    body {
      font-family: "Lato", sans-serif;
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
    