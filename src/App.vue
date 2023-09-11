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
  <div>
    <AppHeader></AppHeader>
    <AppMain></AppMain>
    <AppFooter></AppFooter>
  </div>
</template>

<style>
/*generiche*/
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
img {
  max-width: 100%;
}
.container {
  width: 80%;
  margin: auto;
}
</style>
