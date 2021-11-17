<template>
   <div>
      <div id="main" class="block bg-gradient-to-l from-red-200 via-red-600 to-blue-800 p-10 w-50 h-50">
         <NavBar/>
         <div id="collage" class="flex flex-col justify-center items-center">
         <DynamicImage />
         </div>
      </div>
  </div>
</template>

<script>
import DynamicImage from '../components/DynamicImage.vue';
import NavBar from '../components/NavBar.vue'
export default {
   components: {
      NavBar,
      DynamicImage,
      },
  }
</script>
