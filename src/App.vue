<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";

export default {
  data() {
    return {
      title: "",
    };
  },
  components: { AppHeader, AppMain },
};
</script>

<template>
  <div class="container">
    <AppHeader></AppHeader>
    <AppMain></AppMain>
  </div>
</template>

<style>
.container {
  width: 80%;
  background-color: aqua;
  margin: auto;
}
</style>
