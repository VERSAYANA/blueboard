<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
}
#app {
  --primary-color: #2196F3;
}
</style>
