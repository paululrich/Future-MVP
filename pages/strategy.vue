<template>
  <div class="navbar">
      <h1 style="color:black; z-index: 1; flex-grow: 1;">Strategy</h1>
      <span style="font-size:35px;cursor:pointer; padding-right: 30px;padding-top: 14px;" @click="openNav()">&#9776 </span>
    </div>
    <div id="mySidenav" class="sidenav">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav()">&times;</a>
      <a href="/">Home</a>
      <a style="color:#f1f1f1 !important;">Strategy</a>
      <a href="/clients">Clients</a>
      <a href="/partner">Partner</a>
      <a href="/about_us">About us</a>
      <a href="/contact">Contact</a>
    </div>
    

    <br> 
    <br> 


<p>
    <center>
  <img  src="https://static.wixstatic.com/media/3a6766_1f1987fa77d64f5cadd722bce4fca4ab~mv2.jpg/v1/fill/w_410,h_188,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/Future_MVP_Blk%20New-%20Desk%20top%20JPG_JPG.jpg" 
  alt="Future MVP" align="center" style="width:400px;height:300px;"> </center></p>
  <p align="center" style="font-size:30px">   

    <b>At Future MVP, our mission is crystal clear: to unearth raw talent from the depths of College 
      and High School football and sculpt them into NFL-caliber athletes. To achieve this ambitious goal, 
      we've devised a comprehensive strategy that encompasses talent scouting, rigorous training, and strategic 
      promotion.</b></p>
      <br>
      <br>

      

      <p align="left" style="font-size:20px"> 
<b>Scouting Excellence:</b> We have assembled a team of expert scouts who leave no stone unturned in the quest to identify
 the brightest prospects. From College campuses to High School championships, our scouts are on a constant lookout 
 for exceptional athletes with the potential to shine in the NFL.
 <br>
 <br>
 <b>Elite Training Facilities:</b> Once identified, our Future MVP recruits undergo intensive training at state-of-the-art
 facilities. We leave no room for mediocrity, instilling discipline, honing skills, and enhancing physical conditioning 
 to ensure they are at their peak when they reach the NFL tryouts.
<br>
<br>
<b>Strategic Promotion:</b> Promotion is at the core of our strategy. We leverage our extensive network of connections in the 
NFL to provide opportunities for our talents. From arranging private workouts to showcasing their skills at high-profile
 events, we go above and beyond to ensure our prospects get noticed by the right people.
<br>
<br>
<b>Mentorship and Guidance:</b> Beyond the physical aspect, we understand the importance of mental preparedness. Our athletes
 receive mentorship and guidance from former NFL stars and sports psychologists to equip them with the mental fortitude 
 required to succeed at the highest level.
<br>
<br>
<b>Community Engagement:</b> We believe in giving back to the communities that nurture these talents. We engage in community 
 outreach programs, inspiring young athletes to dream big and providing resources to help them achieve their goals.
<br>
<br>
At Future MVP, we're not just a company; we're a dream factory, churning out NFL stars of tomorrow. Our strategy is
rooted in dedication, hard work, and an unwavering belief in the potential of our athletes. Together, we aim to redefine 
 the future of the NFL, one MVP at a time.
  </p> 


    
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
    </style>
    
    
    <script setup>
       function openNav() {
      document.getElementById("mySidenav").style.width = "250px";
    }
    
    function closeNav() {
      document.getElementById("mySidenav").style.width = "0";
    }
    </script> 