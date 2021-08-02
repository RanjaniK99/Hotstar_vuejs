<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="100%"
      img-height="400"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd" 
    >
      
      <b-carousel-slide img-src="https://i.ytimg.com/vi/ev2YXBpz304/maxresdefault.jpg">
        </b-carousel-slide>
      <b-carousel-slide img-src="https://img1.hotstarext.com/image/upload/f_auto,t_hcdl/sources/r1/cms/prod/7897/977897-h">
      </b-carousel-slide>
      <b-carousel-slide img-src="https://img1.hotstarext.com/image/upload/f_auto,t_web_hs_2_5x/sources/r1/cms/prod/9621/969621-h">
      </b-carousel-slide>
      <b-carousel-slide img-src="https://img1.hotstarext.com/image/upload/f_auto,t_web_hs_2_5x/sources/r1/cms/prod/4600/674600-h">
       </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
  export default {
      name:'Carousel',

    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }
</script>
<style>
.carousel{
  width:100% !important;
  height:400px !important;
}
.w-100{
  width:100% !important;
  height:400px !important;
}
@media screen and (min-width: 70px) and (max-width: 760px) {
  .carousel {
    width: 100% !important;
    height: 200px !important;
  }
  .w-100 {
    width: 100% !important;
    height: 200px !important;
  }
}
@media screen and (min-width: 760px) and (max-width: 1024px) {
  .carousel {
    width: 100% !important;
    height: 300px !important;
  }
  .w-100 {
    width: 100% !important;
    height: 300px !important;
  }
}
</style>