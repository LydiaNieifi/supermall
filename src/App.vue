<template>
  <div id="app">
    <keep-alive exclude="Detail">
      <router-view></router-view>
    </keep-alive>
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import MainTabBar from "@/components/content/mainTabbar/mainTabBar.vue";
export default {
  name: "MyApp",
  components: {
    MainTabBar,
  },
};
</script>

<style lang="less" scoped>
@import url("./assets/css/base.css");
</style>