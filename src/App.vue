<template>
  <div id="app">

    <div id="nav">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-8">
            <router-link to="/" class="navlink">Home</router-link>
            <router-link to="/about" class="navlink">About</router-link>
            <router-link to="/register" class="navlink">Register</router-link>
            <router-link to="/download" class="navlink">Download</router-link>
          </div>
          <div class="col-md-4 text-md-right">
            <button class="btn btn-primary">Login</button>
          </div>
        </div>
      </div>
    </div>
      <router-view/>
   

    <div class="footer card-footer">
      <div class="container text-right">
        <p class="pt-2">
          Site by Vista Copyright @ 2020
        </p>
      </div>
    </div>
  </div>
</template>