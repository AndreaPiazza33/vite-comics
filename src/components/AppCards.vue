<script>
export default {
  data() {
    return {};
  },
  props: {
    img: String,
    title: String,
  },
};
</script>
<template>
  <div class="cards">
    <div>
      <img :src="img" alt="" />
    </div>
    <div>
      <h3>{{ title }}</h3>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.cards {
  width: calc((100% / 6) - 1rem);

  img {
    max-width: 100%;
  }
}
</style>
