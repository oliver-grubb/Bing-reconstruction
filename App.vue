<template>
  <div id="app">
    <Background />
    <div class="body">
      <TopBar />
      <SearchBar />
    </div>
    <div class="bottombar">
      <BottomBar />
    </div>
  </div>
</template>

<script>
import Background from "./components/Background.vue";
import SearchBar from "./components/SearchBar.vue";
import TopBar from "./components/TopBar.vue";
import BottomBar from "./components/BottomBar.vue";

export default {
  name: "app",
  components: {
    SearchBar,
    Background,
    TopBar,
    BottomBar
  }
};
</script>

<style>
.body {
  margin-left: 12.1%;
  margin-right: 9.5%;
}
.bottombar {
  margin-left: 8.5%;
}
</style>
