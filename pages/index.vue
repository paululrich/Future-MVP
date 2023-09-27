<!--HTML-->
<template>
  
  <img src="https://2kolf.com/wp-content/uploads/2020/10/nfl-sunday-ticket-banner-S20.jpg" 
  alt="Picture">

  <span style="font-size:35px;cursor:pointer;float:right" @click="openNav()">&#9776;</span> 
  <div id="mySidenav" class="sidenav">
    <nav>
  <a href="javascript:void(0)" class="closebtn" @click="closeNav()">&times;</a>
  <a href="/strategy">Strategy</a>
  <a href="/clients">Clients</a>
  <a href="/partner">Partner</a>
  <a href="/about_us">About us</a>
  <a href="/contact">Contact</a>
    </nav>
</div>




<p>
    <center>
  <img  src="https://static.wixstatic.com/media/3a6766_1f1987fa77d64f5cadd722bce4fca4ab~mv2.jpg/v1/fill/w_410,h_188,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/Future_MVP_Blk%20New-%20Desk%20top%20JPG_JPG.jpg" 
  alt="Future MVP" align="center" style="width:400px;height:300px;"> </center></p>


  <p align="center" style="font-size:30px">   

    <b>Welcome to Future MVP, where dreams take flight <br> and champions are born. 
    Our mission is to unearth extraordinary talent, <br> sculpt it into greatness, and guide it 
    towards the pinnacle of success in the NFL.</b>
  </p> 

  <br>
  
<br>

  <h2 text-align="left" style="font-size:35px;">NEWS</h2>


  <div class="row">
  <div class="column">
    <a  target="_blank" href="https://www.nfl.com/news/chris-jones-new-one-year-deal-with-chiefs-worth-up-to-25-million-kansas-city-has">
    <img src="https://cdn.vox-cdn.com/thumbor/VjCJlATlrAAmC9ZPw_FF71bt_sc=/0x0:4966x3311/1200x800/filters:focal(2042x772:2836x1566)/cdn.vox-cdn.com/uploads/chorus_image/image/72485160/usa_today_16601357.0.jpg" 
    alt="Chris Jones" @click="myFunction('Chris Jones', 'https://cdn.vox-cdn.com/thumbor/VjCJlATlrAAmC9ZPw_FF71bt_sc=/0x0:4966x3311/1200x800/filters:focal(2042x772:2836x1566)/cdn.vox-cdn.com/uploads/chorus_image/image/72485160/usa_today_16601357.0.jpg');"></a>
    <div class="overlay">
    <div class="text"><b>Chris Jones new one-year deal with Chiefs <br> worth up to $25 million. Sep 2023</b></div>
  </div>
  </div>


  <div class="column">
    <a target="_blank" href="https://www.theguardian.com/sport/2023/sep/06/nick-bosa-contract-san-francisco-49ers-record">
    <img src="https://www.tipico.de/wett-tipps/wp-content/uploads/2023/09/nick-bosa-49-ers.jpg" 
    alt="Nick Bosa" @click="myFunction('Nick Bosa', 'https://www.tipico.de/wett-tipps/wp-content/uploads/2023/09/nick-bosa-49-ers.jpg');"></a>
    <div class="overlay">
    <div class="text"><b>49ers Nick Bosa ends holdout with record<br> $170m contract extension. Sep 2023</b> </div>
  </div>
  </div>


  <div class="column">
    <a  target="_blank" href="https://www.dazn.com/en-US/news/football/la-chargers-qb-justin-herbert-signs-nfl-record-deal/14i4qa89m57na1d4p1kw8s1hgm">
    <img src="https://images.sportschau.de/image/3b3df382-be59-4e81-8e25-65f3762f6cfa/AAABiZHokfw/AAABibBxrfI/16x9-1920/justin-herbert-102.jpg" 
    alt="Justin Herbert" @click="myFunction('Justin Herbert', 'https://images.sportschau.de/image/3b3df382-be59-4e81-8e25-65f3762f6cfa/AAABiZHokfw/AAABibBxrfI/16x9-1920/justin-herbert-102.jpg');"></a>
    <div class="overlay">
    <div class="text"><b>LA Chargers QB Justin Herbert <br>signs NFL record deal. Jul 2023 </b></div>
  </div>
  </div>


  <div class="column">
    <a  target="_blank" href="https://www.mirror.co.uk/sport/other-sports/american-sports/joe-burrow-contract-cincinnati-bengals-30916746#google_vignette">
    <img src="https://on3static.com/cdn-cgi/image/height=417,width=795,quality=90,fit=cover,gravity=0.5x0.5/uploads/dev/assets/cms/2023/09/17215449/joe-burrow.jpg" 
    alt="Joe Burrow" @click="myFunction('Joe Burrow', 'https://on3static.com/cdn-cgi/image/height=417,width=795,quality=90,fit=cover,gravity=0.5x0.5/uploads/dev/assets/cms/2023/09/17215449/joe-burrow.jpg');">
  </a></div>
  <div class="overlay">
    <div class="text"><b>Joe Burrow contract structure emerges with huge
     guarantees and eye-catching incentives. Sep 2023</b> </div>
  </div>
</div>

<!-- The expanding image container -->
<div class="container">
  <!-- Close the image -->
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>

  <!-- Expanded image -->
  <img id="expandedImg" style="width:100%">

  <!-- Image text -->
  <div id="imgtext"></div>
</div>
  
  





</template>







<!--CSS-->>

<style scoped>

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

/* The grid: Four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 10px;
}

/* Style the images inside the grid */
.column img {
  opacity: 0.8; 
  cursor: pointer; 
}

.column img:hover {
  opacity: 1;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The expanding image container */
.container {
  position: relative;
  display: none;
}

/* Expanding image text */
#imgtext {
  position: absolute;
  bottom: 15px;
  left: 15px;
  color: white;
  font-size: 20px;
}

/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10px;
  right: 15px;
  color: white;
  font-size: 35px;
  cursor: pointer;
}










img{width:100%;height:100%;}   





h2 {text-align: left; color:rgb(15, 10, 9); font-size:220%; font-size:10px}
p {background-color: white;border-color: black;}
a:link {
color: black;
background-color: transparent;
text-decoration: none;
}

a:visited {
color: black;
background-color: transparent;
text-decoration: none;
}

a:hover {
color: grey;
background-color: transparent;
text-decoration: none;
}

a:active {
color: black;
background-color: transparent;
text-decoration: none;
}
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




</style>











<!--JAVA-->>
<script setup>
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = 0
}

function myFunction(name, url) {
  var expandImg = document.getElementById("expandedImg");
  var imgText = document.getElementById("imgtext");
  expandImg.src = url;
  imgText.innerHTML = name;
  expandImg.parentElement.style.display = "block";
}


</script>