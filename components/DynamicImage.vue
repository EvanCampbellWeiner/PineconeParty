<template>
  <div>
    <img :src="pineconeImage" class="w-50 max-w-screen-md max-h-screen-md">
  </div>
</template>

<script>
export default {
    computed: {
    pineconeImage () {

      const fileName = Math.floor(Math.random()*29);

      return require(`../assets/images/pinecone/pinecone${fileName}.jpg`) // the module request
    }
  }
}
</script>   