<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <!-- npm install @material/top-app-bar &&
  npm install @material/banner &&
  npm install @material/button &&
  npm install @material/fab &&
  npm install @material/card &&
  npm install @material/checkbox &&
  npm install @material/chips &&
  npm install @material/data-table &&
  npm install @material/dialog &&
  npm install @material/image-list &&
  npm install @material/list &&
  npm install @material/menu &&
  npm install @material/drawer &&
  npm install @material/drawer &&
  npm install @material/radio &&
  npm install @material/snackbar &&
  npm install @material/slider &&
  npm install @material/switch &&
  npm install @material/tab-bar &&
  npm install @material/textfield &&
  npm install @material/tooltip -->
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
