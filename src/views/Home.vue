<template>
  <div class="home">
     <Carousel />
    <Submovie/>
  </div>
</template>

<script>
import Carousel from '../components/Carousel.vue'
import Submovie from '../components/Submovie.vue'

export default {
  components: {
    Carousel,
    Submovie,
  },
};
</script>
<style></style>