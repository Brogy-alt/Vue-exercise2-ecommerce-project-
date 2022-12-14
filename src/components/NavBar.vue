<template>
    <body>
        
  
    <div class="topnav">
  <a class="active" href="">Home</a>
  <a href="products">Products</a>
  <a href="about">About</a>
  <a href="admin">Admin</a>
  <a href="contact">Contact</a>
  <!-- <a href="#about" class="split">Help</a> -->
</div>

  </body>
  </template>

<script>
 export default {
    name: 'NavBar',

 }
 </script>
 

<style scoped>

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create a right-aligned (split) link inside the navigation bar */
.topnav a.split {
  float: right;
  background-color: #04AA6D;
  color: white;
}


</style>