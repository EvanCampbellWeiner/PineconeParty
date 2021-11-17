<template>
   <div>
      <div id="main" class="bg-gradient-to-t from-orange-200 to-blue-400 m-10 w-full h-full">
         <NavBar/>
         <div id="collage" class="flex flex-col justify-center items-center m-10">
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
