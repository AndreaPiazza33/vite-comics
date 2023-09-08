<script>
export default {
  data() {
    return {
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
  <div id="header-container">
    <!--contenitore logo DC-->
    <div>
      <img src="../../public/img/dc-logo.png" alt="" />
    </div>
    <!--contenitore navbar-->
    <div id="link-header-container">
      <a href="">link</a>
      <a href="">link</a>
      <a href="">link</a>
      <a href="">link</a>
      <a href="">link</a>
      <a href="">link</a>
      <a href="">link</a>
      <a href="">link</a>
      <a href="">link</a>
      <a href="">link</a>
    </div>
  </div>
</template>
<style>
#header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
#link-header-container {
  display: flex;
  flex-direction: row;
  gap: 1rem;
}
</style>
