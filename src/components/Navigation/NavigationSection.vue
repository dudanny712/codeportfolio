<template>
  <div>
    <nav class="navbar frame--page">
      <img class="navbar__logo" src="../../assets/logo.svg" />
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
        <li><router-link to="/projects">Projects</router-link></li>
        <li><router-link to="/contact">Contact</router-link></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavigationSection",
};
</script>

<style scoped lang="scss">
@import "../../styles/colors.scss";
@import "../../styles/styles.scss";
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;

  &__logo {
    height: 100px;
    width: 100px;
  }

  ul {
    display: flex;
    list-style: none;
    li {
      margin: 0 16px;
      a {
        color: $text;
        text-decoration: none;
      }
      a:hover {
        color: $secondary;
      }
    }
  }
}
</style>
