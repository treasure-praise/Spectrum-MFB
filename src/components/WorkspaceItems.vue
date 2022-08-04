<template>
  <div class=" flex-col w-4/5 md:w-1/5  text-center">
    <div class="w-32 h-32 bg-white mx-auto mb-6 border">
      <img class="" src="../assets/icons/{{icon}}" alt="" />
    </div>
    <p class="mx-auto w-2/3 text-[#0A2E65] text-lg font-bold">{{ text }}</p>
  </div>
</template>

<script>
export default {
  name: "WorkspaceItems",
  props: {
    text: {
      type: String,
      default: "delayed Bulk Payment",
    },
    icon:{
        type: String,
        default:"delayed.svg"
    }
  },
};
</script>

<style lang="scss" scoped></style>
