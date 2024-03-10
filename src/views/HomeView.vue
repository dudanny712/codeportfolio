<template>
  <div class="home">
    <NavigationSection />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import NavigationSection from "@/components/Navigation/NavigationSection.vue";

import HeaderBar from "@/components/HeaderBar/HeaderBar.vue";
import FooterComponent from "@/components/Footer/FooterComponent.vue";

@Options({
  components: {
    HeaderBar,
    NavigationSection,
    FooterComponent,
  },
})
export default class HomeView extends Vue {}
</script>

<style lang="scss">
.home {
  height: 100%;
  width: 100%;
  background-color: $background;
}
</style>
