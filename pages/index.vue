<template>
  <div>
    <div class="box">
      <principal />
    </div>
  </div>
</template>

<script>
export default {
  components: true,
}
</script>

<style lang="scss">
.box {
  height: 100vh;
  width: 100%;
  background-image: url(/background.jpg);
  background-size: cover;
  background-attachment: fixed;
  background-position: bottom 50% left 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
}
.box2 {
  height: 100vh;
  width: 100%;
  background-color: white;
  color: black;
}
</style>
