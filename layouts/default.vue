<template>
  <v-app dark>
    <navigation />
    <nuxt />
  </v-app>
</template>
<script>
export default {
  components: true,
}
</script>

<style lang="scss">
.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s;
}
.page-enter,
.page-leave-to {
  opacity: 0;
}

.layout-enter-active,
.layout-leave-active {
  transition: opacity 0.5s;
}
.layout-enter,
.layout-leave-to {
  opacity: 0;
}

.slide-bottom-enter-active,
.slide-bottom-leave-active {
  transition: opacity 0.25s ease-in-out, transform 0.25s ease-in-out;
}
.slide-bottom-enter,
.slide-bottom-leave-to {
  opacity: 0;
  transform: translate3d(0, 15px, 0);
}
.box {
  height: 100vh;
  width: 100%;
  background-image: url(/background.jpg);
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>