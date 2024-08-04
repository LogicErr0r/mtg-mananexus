<!-- src/components/HomeView.vue -->

<template>
  <div>
    <div class="topnav">
      <router-link class="active" to="/">Home</router-link>
      <router-link to="/formats">Formats</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/login">Register/Login</router-link>
      <router-link to="/news">News</router-link>
    </div>

    <div class="homepagetitle">
      <h1>Mana Nexus</h1>
    </div>

    <div class="newstitle">
      <h1>Important Updates</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView'
}
</script>

<style scoped>
/* Home Page Title */
.homepagetitle {
  background-color: Black;
  text-align: Center;
  color: Green;
}

/* Navgation Bar */
/* Add a black background color to the top navigation */
.topnav {
  background-color: Black;
  overflow: hidden;
}

/* Style the links inside the navigation bar */
.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Add a color to the active/current link */
.topnav a.active {
  background-color: #04AA6D;
  color: white;
}
</style>
