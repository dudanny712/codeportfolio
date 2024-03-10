<template>
  <HeaderBar />
  <div id="app">
    <router-link to="/"> </router-link>
  </div>

  <router-view />
  <FooterComponent />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import FooterComponent from "@/components/Footer/FooterComponent.vue";
import HeaderBar from "@/components/HeaderBar/HeaderBar.vue";
import NavigationSection from "@/components/Navigation/NavigationSection.vue";

@Options({
  components: {
    HeaderBar,
    NavigationSection,
    FooterComponent,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
#app {
  background-color: $background;
}
</style>
