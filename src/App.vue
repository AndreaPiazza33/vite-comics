<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  data() {
    return {
      title: "",
    };
  },
  components: { AppHeader, AppMain, AppFooter },
};
</script>

<template>
  <div class="container">
    <AppHeader></AppHeader>
    <AppMain></AppMain>
    <AppFooter></AppFooter>
  </div>
</template>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
.container {
  width: 80%;
  background-color: aqua;
  margin: auto;
}
</style>
