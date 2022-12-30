<template>
  <div class="home">
    <CarouselVue class="carousel">
      <SlideVue>
        <div>
          <p>Hello</p>
        </div>
      </SlideVue>
    </CarouselVue>
  </div>
</template>

<script>
import CarouselVue from '@/components/CarouselVue.vue';
import SlideVue from '@/components/SlideVue.vue';

export default {
  name: 'HomeVue',
  components: {
    CarouselVue,
    SlideVue
  },
  setup() {
    
  }
}
</script>

<style lang="scss" scoped>
.carousel {
  max-height: 100vh;
  height: 100vh;
  
}
</style>
