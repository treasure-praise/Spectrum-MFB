<template>
  <div class=" w-full md:w-1/5  text-center mb-8">
    <div class="w-32 h-32 bg-white mx-auto mb-6 border ">
      <img class="w-12 text-center block" :src="[imgUrl]" alt="" />
    </div>
    <p class="mx-auto w-2/3 text-[#0A2E65] text-lg font-bold">{{ text }}</p>
  </div>
</template>

<script>
const images= [
      {
        id:"0",
        url:"../assets/icons/delayed.svg",
        title:"",
        des:"some text",
      },
      {
        id:"1",
        url:"../assets/img2.jpg",
        title:"some text",
        des:"some text",
      },
      {
        id:"2",
        url:"../assets/img3.jpg",
        title:"some text",
        des:"some text",
      },
    ]
export default {
  name: "WorkspaceItems",
  props: ['text','imgUrls']
};
</script>

<style lang="scss" scoped></style>
