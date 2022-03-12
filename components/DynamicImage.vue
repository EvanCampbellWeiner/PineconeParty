<template>
  <div class="border-md border-white border-w-2 flex flex-col justify-center items-center">
    <button class="bg-white text-black text-md p-4 rounded-md m-4" @click="updatePinecone()"><img src="~/assets/images/pinecone/pinecone.jpg" class="w-10 h-10"/></button>
    <img :src="require('~/assets/images/pinecone/pinecone'+id+'.jpg')" class="w-auto h-96">
  </div>
</template>

<script>
export default {
    data() {
    return {
            id: 1,
        };
    },
    mounted(){
        this.id = Math.floor(Math.random()*29);
    },
    methods: {
        updatePinecone() {
            const newId = Math.floor(Math.random()*29);
            this.id = newId;
        }
    }
}
</script>   