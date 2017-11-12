<template>
  <div id="app">
    <SideBar/>
    <router-view/>
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
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  display: flex;
  height: 100vh;
}
</style>
