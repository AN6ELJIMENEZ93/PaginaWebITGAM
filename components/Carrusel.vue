<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        img-src="@/assets/images/Carrusel/SeminarioTitulacion.jpg"
        a href="@/assets/documents/Carrusel/seminario1.pdf"
      ></b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide 
          img-src="@/assets/images/Carrusel/CalendarioAgosto-Diciembre.jpg">
      </b-carousel-slide>

      <b-carousel-slide 
          img-src="@/assets/images/Carrusel/muestra.jpeg">
      </b-carousel-slide>

    </b-carousel>

  </div>
</template>

<script>
  export default {
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
