<template>
  <div id="app">
    <div id="nav">
      <!--
      <router-link to="/about">About</router-link> |-->
      <router-link to="/">Home</router-link> |
      <router-link to="/designer">Ballot Designer</router-link> |
      <router-link to="/register">Register</router-link> |
      <router-link to="/voting">Voting Simulator</router-link> |
      <router-link to="/bcView">Blockchain Viewer</router-link> |
      <router-link to="/results">Results</router-link> |
    </div>
    <router-view/>
  </div>
</template>

<!-- if you change background change color here, change it in index.html too-->
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  background-color: #1a1f27; 
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #ffffff;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
