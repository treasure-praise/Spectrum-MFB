<template>
  <div class="w-3/5 h-80 bg-white mx-auto py-10 rounded-2xl flex flex-col ">
    <button class="  float-right">
      <img src="../assets/icons/close.svg" alt="" />
    </button>
    <div
      class="   py-10  flex flex-col items-center"
    >
      <img class="mb-4" src="../assets/icons/DialogSuccess.svg" alt="" />
      <h2 class="text-[#0A2E65] mb-6 font-bold text-2xl">Sent</h2>
      <p class="mb-8 text-[#6C82A3] text-sm">Transfer Request has been sent</p>
      <div class="flex gap-8">
        <StatusButton text="Proceed" color="ED3237" />
      <StatusButton text="View Status" color="ED3237" />
      </div>
      
    </div>
  </div>
</template>

<script setup>
import StatusButton from "../components/StatusButton.vue";
</script>

<style lang="scss" scoped></style>
