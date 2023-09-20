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

<h2 style="font-size:50px;">Future MVP</h2>

<br> 
  <p text-align: center; color:rgb(15, 10, 9); style="font-size:30px">   

    Welcome to Future MVP, where dreams take flight and champions are born. 
    Our mission is to unearth extraordinary talent, sculpt it into greatness, and guide it 
    towards the pinnacle of success in the NFL
  </p> 

<br> 
  <p style="font-size:15px;position:relative; left:80px; top:120px">
    Chris Jones new one-year deal with Chiefs <br> worth up to $25 million. Sep 2023 
    <b><a  href="https://www.nfl.com/news/chris-jones-new-one-year-deal-with-chiefs-worth-up-to-25-million-kansas-city-has">NFl</a></b>
  </p>         
  <p style="font-size:15px;position:relative; right:140px; top:320px">49ers Nick Bosa ends holdout with record<br> $170m contract extension. Sep 2023 <b><a href="https://www.theguardian.com/sport/2023/sep/06/nick-bosa-contract-san-francisco-49ers-record">The Guardian</a></b></p>
  <p style="font-size:15px;position:relative; left:340px; top:220px">LA Chargers QB Justin Herbert <br>signs 
    NFL record deal. Jul 2023 <b><a href="https://www.dazn.com/en-US/news/football/la-chargers-qb-justin-herbert-signs-nfl-record-deal/14i4qa89m57na1d4p1kw8s1hgm">DAZN</a></b></p>
  <p style="font-size:15px;position:relative; right:40px; top:320px">Joe Burrow contract structure emerges with huge <br>guarantees and eye-catching incentives. Sep 2023 <b><a href="https://www.mirror.co.uk/sport/other-sports/american-sports/joe-burrow-contract-cincinnati-bengals-30916746#google_vignette">The Mirror</a></b></p>


  <meta name="viewport" content="width=device-width, initial-scale=1">
  <div class="container">
  <a  href="https://www.nfl.com/news/chris-jones-new-one-year-deal-with-chiefs-worth-up-to-25-million-kansas-city-has"><img src="https://cdn.vox-cdn.com/thumbor/VjCJlATlrAAmC9ZPw_FF71bt_sc=/0x0:4966x3311/1200x800/filters:focal(2042x772:2836x1566)/cdn.vox-cdn.com/uploads/chorus_image/image/72485160/usa_today_16601357.0.jpg" alt="Chris Jones" class="image"></a>
  <div class="overlay">
    <div class="text">Chris Jones new one-year deal with Chiefs <br> worth up to $25 million. Sep 2023</div>
  </div>
  </div>

  
  <br>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <div class="container">
  <a  href="https://www.theguardian.com/sport/2023/sep/06/nick-bosa-contract-san-francisco-49ers-record"><img src="https://www.tipico.de/wett-tipps/wp-content/uploads/2023/09/nick-bosa-49-ers.jpg" alt="Nick Bosa" class="image"></a>
  <div class="overlay">
    <div class="text">49ers Nick Bosa ends holdout with record<br> $170m contract extension. Sep 2023 </div>
  </div>
  </div>

  <br>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <div class="container">
  <a  href="https://www.dazn.com/en-US/news/football/la-chargers-qb-justin-herbert-signs-nfl-record-deal/14i4qa89m57na1d4p1kw8s1hgm">
    <img src="https://images.sportschau.de/image/3b3df382-be59-4e81-8e25-65f3762f6cfa/AAABiZHokfw/AAABibBxrfI/16x9-1920/justin-herbert-102.jpg" alt="Justin Herbert" class="image"></a>
  <div class="overlay">
    <div class="text">LA Chargers QB Justin Herbert <br>signs NFL record deal. Jul 2023 </div>
  </div>
  </div>

  <br>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <div class="container">
  <a  href="https://www.theguardian.com/sport/2023/sep/06/nick-bosa-contract-san-francisco-49ers-record"><img src="https://www.tipico.de/wett-tipps/wp-content/uploads/2023/09/nick-bosa-49-ers.jpg" alt="Nick Bosa" class="image"></a>
  <div class="overlay">
    <div class="text">49ers Nick Bosa ends holdout with record<br> $170m contract extension. Sep 2023 </div>
  </div>
  </div>

</template>








<!--CSS-->>
<style>
.container {
  position: relative;
  width: 50%;
}

.image {
  opacity: 1;
  display: block;
  width: 50px;
  height: 50px;
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
</script>