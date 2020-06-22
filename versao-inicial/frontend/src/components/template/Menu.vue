<template>
  <aside class="menu" v-show="isMenuVisible"></aside>
</template>

<script>
import { mapState } from "vuex";

export default {
  name: "Menu",
  computed: mapState(["isMenuVisible"])
};
</script>

<style>
.menu {
  grid-area: menu;
  background: linear-gradient(to right, #26c7b1, #5e7777);

  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
}

.menu:hover {
  background-color: rgba(0, 0, 0, 0.2);
}
</style>
