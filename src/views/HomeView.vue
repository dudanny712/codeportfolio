<template>
  <div class="home">
    <NavigationSection />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import NavigationSection from "@/components/Navigation/NavigationSection.vue";

@Options({
  components: {
    NavigationSection,
  },
})
export default class HomeView extends Vue {}
</script>

<style lang="scss"></style>
