<template>
  <div>
    <div class="container"> <br><br><br>
      <Carrusel />
    </div>
    <Cuerpo />
  </div>
</template>

<script>
import { largeCardSections, smallCardSections } from "@/assets/data.js";
import Default from "../layouts/default.vue";
export default {
   
    components: { Default }
}
</script>

<style>

</style>