<script>
export default {
  data() {
    return {
      linkIndex: 0,
      headerLinks: [
        {
          title: "CHARACTERS",
          link: "#",
        },
        {
          title: "COMICS",
          link: "#",
        },
        {
          title: "MOVIES",
          link: "#",
        },
        {
          title: "TV",
          link: "#",
        },
        {
          title: "GAMES",
          link: "#",
        },
        {
          title: "COLLECTIBLES",
          link: "#",
        },
        {
          title: "VIDEOS",
          link: "#",
        },
        {
          title: "FANS",
          link: "#",
        },
        {
          title: "NEWS",
          link: "#",
        },
        {
          title: "SHOP",
          link: "#",
        },
      ],
    };
  },
};
</script>

<template>
  <!--contenitore header-->
  <div class="header-container">
    <!--contenitore logo DC-->
    <div>
      <img src="/img/dc-logo.png" alt="" />
    </div>
    <!--contenitore navbar-->
    <div class="link-header-container">
      <div v-for="link in headerLinks">
        <a :href="link.link">{{ link.title }}</a>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}
.link-header-container {
  display: flex;
  flex-direction: row;
  gap: 1rem;
  color: hsl(0, 0%, 44%);
  a {
    color: inherit;
    text-decoration: none;
    &:hover {
      text-decoration: underline;
      color: hsl(208.91deg 98.41% 49.22%);
    }
  }
}
</style>
