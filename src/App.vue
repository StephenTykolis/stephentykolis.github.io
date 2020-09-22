<template>
  <div id="app" class="center">
    <MainPage />
    <Menu />
  </div>
</template>

<script>
import MainPage from "./components/MainPage.vue";
import Menu from "./components/Menu.vue";

export default {
  name: "App",
  components: {
    MainPage,
    Menu,
  },
};
</script>

<style>
body {
  background-color: #136f63;
  color: #e0ca3c;
  font-family: "Work Sans", sans-serif;
}
* {
  margin: 0;
  padding: 0;
  outline: none;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
}

html {
  font-size: 62.5%;
}
</style>
