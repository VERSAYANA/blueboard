<template>
  <div id="app">
    <div id="content">
      <router-view/>
    </div>
    <Nav />
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import Nav from '@/components/Nav.vue';
export default Vue.extend({
  name: 'app',
  components: {
    Nav,
  },
})
</script>


<style lang="scss">
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
}
#app {
  --primary-color: #2196F3;

  height: 100%;
  display: flex;
  flex-direction: column;
  // overflow: auto;
}
#content {
  overflow: auto;
  flex: 1;
}
#nav {
  height: 64px;
  background-color: gray;
}

</style>
