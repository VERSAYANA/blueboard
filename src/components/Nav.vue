<template>
  <div id="nav">
    <div>
      <svg viewBox="0 0 24 24">
        <path
          d="M19,3H5C3.89,3 3,3.89 3,5V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5C21,3.89 20.1,3 19,3M19,5V19H5V5H19Z"
        ></path>
      </svg>
    </div>
    <div>
      <svg viewBox="0 0 24 24">
        <path
          d="M19,3H5C3.89,3 3,3.89 3,5V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5C21,3.89 20.1,3 19,3M19,5V19H5V5H19Z"
        ></path>
      </svg>
    </div>
    <div>
      <svg viewBox="0 0 24 24">
        <path
          d="M19,3H5C3.89,3 3,3.89 3,5V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5C21,3.89 20.1,3 19,3M19,5V19H5V5H19Z"
        ></path>
      </svg>
    </div>
    <div>
      <svg viewBox="0 0 24 24">
        <path
          d="M19,3H5C3.89,3 3,3.89 3,5V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5C21,3.89 20.1,3 19,3M19,5V19H5V5H19Z"
        ></path>
      </svg>
    </div>
    <div>
      <svg viewBox="0 0 24 24">
        <path
          d="M19,3H5C3.89,3 3,3.89 3,5V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5C21,3.89 20.1,3 19,3M19,5V19H5V5H19Z"
        ></path>
      </svg>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  name: "Nav"
});
</script>

<style lang="scss" scoped>
#nav {
    height: 56px;
    background-color: bisque;
    display: flex;
    justify-content: space-between;

    div {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;    
    }

    svg {
        fill: black;
        width: 24px;
        height: 24px;
    }
}

</style>

