<template>
  <div id="nav">
    <router-link to="/about">
      <svg viewBox="0 0 24 24">
        <path
          d="M9,22V24H7V22H9M13,22V24H11V22H13M17,22V24H15V22H17M12,15H10V13H12V15M18,15H14V13H18V15M8,11H6V9H8V11M18,11H10V9H18V11M20,20H4A2,2 0 0,1 2,18V6A2,2 0 0,1 4,4H20A2,2 0 0,1 22,6V18A2,2 0 0,1 20,20M4,6V18H20V6H4Z"
        ></path>
      </svg>
    </router-link>

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

  div,a {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;

    &.router-link-active {
      svg {
        fill: var(--primary-color);
      }
    }
  }

  svg {
    fill: black;
    width: 24px;
    height: 24px;
  }
}
</style>
