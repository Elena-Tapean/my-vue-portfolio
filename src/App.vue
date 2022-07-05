<template>
  <div id="app">
    <nav>
      <img src="..\src\assets\logo.png" alt="logo">
      <router-link to="/">Home</router-link> 
      <router-link to="/about">About</router-link> 
      <router-link to="/contact">Contact</router-link> 
      <router-link to="/portfolio">Portfolio</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

img {
  width: 100px;
  height: 30px;
  display: inline;
  padding-right: 300px;
}

nav {
  padding: 20px;
  border-bottom: 1px solid lightgrey;

  a {
    font-weight: bold;
    color: green;
    padding: 70px;

    &.router-link-exact-active {
      color: orange;
    }
  }
}
</style>
