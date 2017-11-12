<template>
  <div class="sideBar">
    <div class="logo">
      <div class="logoImage">CERU<br/>BERU</div>
      <div class="logoText">Portfolio & Blog</div>
    </div>
    <div class="category">
      <div> CV </div>
      <div> Projects </div>
      <hr>
      <div> Javascript </div>
      <div> React </div>
      <div> Vue </div>
      <div> MongoDB </div>
      <div> AWS </div>
      <div> Docker </div>
      <div> Algorithm </div>
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
.category div {
  display: flex;
  flex: 0 0 30px;
  align-items: center;
  justify-content: center;
}
.category div:hover {
  border-right: 4px solid #6bff8d;
  margin-left: 4px;
  cursor: pointer;
}
</style>
