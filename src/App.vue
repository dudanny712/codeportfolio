<template>
  <div id="app"><router-link to="/"></router-link></div>
  <router-view />
</template>

<style lang="scss">
@import "./styles/colors.scss";
#app {
  background-color: $primary;
}
</style>
