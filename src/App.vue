<template>
  <div id="app">
    <my-layot> </my-layot>
  </div>
</template>

<script>
import MyLayot from "./components/Layot.vue";
export default {
  name: "App",
  components: { MyLayot },
};
</script>

<style lang="scss">
* {
  font-size: 16px;
  line-height: 24px;
  color: #170c04;
  font-style: normal;
  font-weight: 400;
}
</style>
