<template>
  <div class="sideBar">
    <div class="logo">
      <div class="logoImage">CERU<br/>BERU</div>
      <div class="logoText">Portfolio & Blog</div>
    </div>
    <div class="category">
      <router-link to="cv" class="routerLink"> CV </router-link>
      <router-link to="project" class="routerLink"> Projects </router-link>
      <hr>
      <router-link to="ิblog" class="routerLink"> Javascript </router-link>
      <router-link to="ิblog" class="routerLink"> React </router-link>
      <router-link to="ิblog" class="routerLink"> Vue </router-link>
      <router-link to="ิblog" class="routerLink"> MongoDB </router-link>
      <router-link to="ิblog" class="routerLink"> AWS </router-link>
      <router-link to="ิblog" class="routerLink"> Docker </router-link>
      <router-link to="ิblog" class="routerLink"> Algorithm </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'sideBar',
};
</script>

<style scoped>
.sideBar {
  display: flex;
  flex: 1;
  flex-direction: column;
  border-right: 1px solid lightgrey;
  min-width: 135px;
}
.logo {
  display: flex;
  flex: 0 0 120px;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  border-bottom: 1px solid lightgrey;
}
.logoImage {
  padding-top: 15px;
}
.logoText {
  display: flex;
  padding-bottom: 15px;

}
.category {
  display: flex;
  flex-direction: column;
  flex: 1;
  padding-top: 10px;
}
.category hr {
  border: none;
  height: 1px;
  background-color: lightgrey;
  margin-left: 15px;
  margin-right: 15px;
}
.routerLink {
  box-sizing: border-box;
  display: flex;
  flex: 0 0 30px;
  align-items: center;
  justify-content: center;
  text-decoration: none;
  color: black;
  cursor: pointer;
  transition: all 0.5s ease;
}
.routerLink:hover {
  font-weight: 600;
  letter-spacing: 1px;
}
.exactActive {
  font-weight: 600;
  letter-spacing: 1px;
  border-right: 4px solid #63ff38;
  /* margin-left: 4px; */
}
</style>
