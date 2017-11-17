<template>
  <div id="app">
    <SideBar/>
    <div id="main">
      <div class="container">
        <router-view/>
      </div>
    </div>
  </div>
</template>

<script>
import SideBar from '@/components/SideBar';

export default {
  name: 'app',
  components: {
    SideBar,
  },
};
</script>

<style>
body {
  margin: 0px;
}
#app {
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
  /* -webkit-font-smoothing: antialiased; */
  /* -moz-osx-font-smoothing: grayscale; */
  display: flex;
  height: 100vh;
}
#main {
  display: flex;
  flex: 5;
  background-color: lightgrey;
  overflow-y: scroll;
  height: 100vh;
}
</style>
