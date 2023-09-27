<template>
  <div class="navbar">
      <h1 style="color:black; z-index: 1; flex-grow: 1;">About us</h1>
      <span style="font-size:35px;cursor:pointer; padding-right: 30px;padding-top: 14px;" @click="openNav()">&#9776 </span>
    </div>
<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" @click="closeNav()">&times;</a>
  <a href="/">Home</a>
  <a href="/strategy">Strategy</a>
  <a href="/clients">Clients</a>
  <a href="/partner">Partner</a>
  <a style="color:#f1f1f1 !important;">About us</a>
  <a href="/contact">Contact</a>
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
</style>


<script setup>
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
</script>
