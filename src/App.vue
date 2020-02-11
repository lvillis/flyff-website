<template>
  <div id="app">

    <div id="nav">
      <router-link to="/" class="navlink">Home</router-link>
      <router-link to="/about" class="navlink">About</router-link>
      <router-link to="/register" class="navlink">Register</router-link>
      <router-link to="/download" class="navlink">Download</router-link>
    </div>
    <router-view/>



  </div>
</template>