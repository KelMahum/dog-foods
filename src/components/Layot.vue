<template>
  <div>
    <div class="full-wrapper">
      <dog-header></dog-header>
      <main>
        <dog-intro></dog-intro>
        <popular-products></popular-products>
        <dog-adoption></dog-adoption>
        <gallery-products></gallery-products>
        <testimonial></testimonial>
        <message></message>
      </main>
    </div>
    <bottom-menu></bottom-menu>
  </div>
</template>

<script>
import DogIntro from "./Intro.vue";
import DogHeader from "./Header.vue";
import PopularProducts from "./Products.vue";
import DogAdoption from "./Adoption.vue";
import GalleryProducts from "./Gallery.vue";
import Testimonial from "./Testimonial.vue";
import Message from "./Message.vue";
import BottomMenu from "./Bottom.vue";

export default {
  components: {
    DogIntro,
    DogHeader,
    PopularProducts,
    DogAdoption,
    GalleryProducts,
    Testimonial,
    Message,
    BottomMenu,
  },
};
</script>

<style lang="scss">
</style>