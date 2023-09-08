<script>
import AppHeader from "./components/AppHeader.vue";

export default {
  data() {
    return {
      title: "",
    };
  },
  components: { AppHeader },
};
</script>

<template>
  <div class="container">
    <AppHeader></AppHeader>
  </div>
</template>

<style>
.container {
  width: 80%;
  background-color: aqua;
  margin: auto;
}
</style>
