<template>
  <div class="header__container">
    <img class="header__logo" src="../../assets/vscode.webp" />
    <SearchBox />
  </div>
</template>
<script lang="ts">
import SearchBox from "./SearchBox.vue";
export default {
  name: "HeaderBar",
  components: {
    SearchBox,
  },
};
</script>
<style scoped lang="scss">
.header {
  &__container {
    padding: 16px;
    display: flex;
    align-items: center;
  }
  &__logo {
    width: 20px;
    height: 20px;
    margin-left: 8px;
  }
}
</style>
