<template>
  <div class="navbar">
      <h1 style="color:black; z-index: 1; flex-grow: 1;">Contact</h1>
      <span style="font-size:35px;cursor:pointer; padding-right: 30px;padding-top: 14px;" @click="openNav()">&#9776 </span>
  </div>

    <div id="mySidenav" class="sidenav">
      <a href="javascript:void(0)" class="closebtn" @click="closeNav()">&times;</a>
      <a href="/">Home</a>
      <a href="/strategy">Strategy</a>
      <a href="/clients">Clients</a>
      <a href="/partner">Partner</a>
      <a href="/about_us">About us</a>
      <a style="color:#f1f1f1 !important;">Contact</a>
    </div>
    




    

<div class="container">
  <h3 style="margin-top: 40px;padding-top: 40px;">Contact Form</h3>
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="country">Country</label>
    <select id="country" name="country">
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">
  </form>
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





    body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #eaeaea;
  padding: 20px;
  width: 80%;
  margin-left: auto;
  margin-right: auto;
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