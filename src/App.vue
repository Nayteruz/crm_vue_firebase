<template>
  <button class="btn">Hello</button>
  <RouterView/>
</template>

<script>
import {RouterView} from "vue-router";

export default {
  setup() {

  },
};
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
@import "materialize-css/dist/css/materialize.min.css";
@import "assets/index.css";

$roboto:'Roboto', sans-serif;
</style>
