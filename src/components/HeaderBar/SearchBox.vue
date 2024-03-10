<template>
  <div class="search-bar">
    <div>
      <span
        ><svg
          class="search-bar__icon"
          width="800px"
          height="800px"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          stroke="#ffffff"
        >
          <g id="SVGRepo_bgCarrier" stroke-width="0" />

          <g
            id="SVGRepo_tracerCarrier"
            stroke-linecap="round"
            stroke-linejoin="round"
          />

          <g id="SVGRepo_iconCarrier">
            <path
              d="M15.7955 15.8111L21 21M18 10.5C18 14.6421 14.6421 18 10.5 18C6.35786 18 3 14.6421 3 10.5C3 6.35786 6.35786 3 10.5 3C14.6421 3 18 6.35786 18 10.5Z"
              stroke="#ffffff"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </g></svg
      ></span>
      Daniel's Porfolio
    </div>
  </div>
</template>

<script>
export default {
  name: "SearchBox",
};
</script>

<style scoped lang="scss">
.search-bar {
  position: relative;
  border: 1px solid #ccc;
  background-color: $secondary;
  width: 100%;
  margin: 0 500px;
  height: 30px;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: $text;

  &__icon {
    width: 15px;
    height: 15px;
    fill: transparent;
    transform: scaleX(-1);
  }
}
</style>
