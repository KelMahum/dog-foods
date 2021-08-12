<template>
  <div class="wrapper">
    <header class="header">
      <div class="header__logo">
        <a href="#"><img src="../assets/images/logo.png" alt="" /></a>
        <a href="#"><div class="header__title">DOG</div></a>
      </div>
      <nav class="header-nav" v-bind:class="{ 'header-nav_active': isActive }">
        <a href="#" class="header-nav__link">Products</a>
        <a href="#" class="header-nav__link">Dog Care</a>
        <a href="#" class="header-nav__link">About</a>
        <a href="#" class="header-nav__link">Popular</a>
      </nav>
      <div class="header-widgets">
        <div class="header-widgets__item">
          <a href="#"><img src="../assets/images/search.svg" alt="" /></a>
        </div>
        <div class="header-widgets__item">
          <a href="#"><img src="../assets/images/cart.svg" alt="" /></a>
        </div>
        <div
          class="header-widgets__item header-widgets__burger"
          @click="isActive = !isActive"
        >
          <a href="#"><img src="../assets/images/burger.svg" alt="" /></a>
        </div>
        <div
          class="header-widgets__item header-widgets__close"
          v-bind:class="{ 'header-nav_active': isActive }"
          v-if="isActive"
          @click="isActive = !isActive"
        >
          <span class="header-widgets__close-line"></span
          ><span class="header-widgets__close-line"></span>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isActive: false,
    };
  },
  methods: {},
};
</script>

<style>
</style>