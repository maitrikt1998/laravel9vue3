<template>
<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="#">SolvedMyCode</a>
    </div>
    <ul class="nav navbar-nav">
        <li><router-link :to="{name:'home'}">Home</router-link></li>
        <li><router-link :to="{name:'contact'}">Contact</router-link></li>
        <li><router-link :to="{name:'register'}">Register</router-link></li>
        <li><router-link :to="{name:'login'}">Login</router-link></li>
    </ul>
  </div>
</nav>
    <div>
        
        <router-view></router-view>
    </div>
</template>