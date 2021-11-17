<template>
  <div>
    <img :src="pineconeImage" class="w-50 max-w-screen-md max-h-screen-md">
  </div>
</template>

<script>
export default {
    computed: {
      pineconeImage () {

         return require(`../assets/images/pinecone/pinecone${Math.floor(Math.random()*29) }.jpg`) // the module request
      }
  },
}
</script>   