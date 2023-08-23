<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link :to="{ name: 'contact' }">Contact</router-link> |
    <a href="https://kun.uz">Kun.uz sayti</a>
  </nav>
  <router-view />
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
body {
  background: #8ca789;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.buttons {
  display: flex;
  gap: 8px;
  justify-content: center;
  margin-top: 20px;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #ffffff;
}
</style>
