<template>
    <div id="main" class="bg-gradient-to-b from-pink-600 via-purple-300 to-blue-600 w-screen h-screen flex flex-col justify-center items-center">
        <div id="collage" class="flex flex-col justify-center items-center">
        <DynamicImage />
        </div>
    </div>
</template>

<script>
import DynamicImage from '../components/DynamicImage.vue';
export default {
   components: {
      DynamicImage,
      },
  }
</script>
