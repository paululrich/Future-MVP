<template>
    <link rel="stylesheet" 
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <div class="card">
  <img :src="bildUrl" alt="John" style="width:100%">
  <h1>{{ name }}</h1>
  <p class="title">{{ teamPosition }}</p>
  <p>{{university}}</p>
  <p><button><a :href="instagramLink"><img src="https://www.nicepng.com/png/detail/1-13041_logo-instagram-with-white-circle-background-png-new.png"></a></button></p>
</div>
    </template>
<style>
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

<script setup lang="ts">
defineProps<{
  name: string;
  bildUrl: string;
  teamPosition: string;
  university: string;
  instagramLink?: string;
}>();
</script>