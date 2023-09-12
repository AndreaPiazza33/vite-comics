<script>
import AppCards from "./AppCards.vue";

export default {
  components: { AppCards },
};
</script>

<template>
  <!--contenuti da inserire-->
  <div class="bg-main">
    <AppCards></AppCards>
  </div>
</template>
<style>
.bg-main {
  background-color: hsl(0deg 0% 10.98%);
  color: white;
}
</style>
