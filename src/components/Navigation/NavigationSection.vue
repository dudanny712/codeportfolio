<template>
  <div class="navbar">
    <span>
      <img class="navbar__logo" src="../../assets/logo.svg" />
    </span>
  </div>
</template>
<script lang="ts">
export default {};
</script>
<style lang="scss">
.navbar {
  height: 50px;
  width: 100%;
  color: white;
  border-bottom: 1px solid white;
  display: flex;
  align-items: center;
  padding: 32px;

  &__logo {
    height: 100px;
    width: 100px;
  }
}
</style>
