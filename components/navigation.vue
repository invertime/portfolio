<template>
  <div class="navigation">
    <div class="navArea">
      <ul>
        <li>
          <nuxt-link to="/" class="link">home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about" class="link">project</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about" class="link">about</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about" class="link">online cv</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about" class="link">contact</nuxt-link>
        </li>
      </ul>
    </div>
    <div class="imgArea"></div>
  </div>
</template>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,600,700,800,900&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
.navigation{
  display: flex;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background: #111;
  transition: 0.2s;
}

.navigation .navArea {
  position: relative;
  width: 50%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.navigation .navArea ul li {
  list-style: none;
}

.navigation .navArea ul li .link {
  font-size: 3em;
  font-weight: 600;
  text-decoration: none;
  color: rgba(255,255,255,0.5);
  transition: all 0.25s;
}

.navigation .navArea ul li:hover .link {
  color: rgba(255,255,255,1);
}

.imgArea {
  position: relative;
  width: 50%;
  height: 100vh;
  background-color: red;
}
</style>
