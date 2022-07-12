<template>
  <div class="w-4/5  px-8 py-2 bg-white mx-auto rounded-2xl">
    <div
      class="  bg-white mx-auto  rounded-2xl flex flex-col"
    >
      <div class="">
        <button class="float-right">
          <img src="../assets/icons/close.svg" alt="" />
        </button>

        <h1
          class="text-[#0A2E65] float-left mt-8 block text-4xl font-bold mb-20"
        >
          Summary
        </h1>
      </div>
      <div class="text-[#0A2E65] w-full  py-3 mx-auto">
        <div class="flex gap-12 border-b py-3 px-4 mx-auto">
          <p class="font-bold w-1/2">Beneficiary Name:</p>
          <p class="w-1/2">Kizito Isifeh</p>
        </div>
        <div class="flex text-[#0A2E65] gap-12 border-b py-3 px-4 mx-auto">
          <p class="font-bold w-1/2">Account Number:</p>
          <p class="w-1/2">2020599742</p>
        </div>
        <div class="flex text-[#0A2E65] gap-12 border-b py-3 px-4 mx-auto">
          <p class="font-bold w-1/2">Ammount:</p>
          <p class="w-1/2">2020599742</p>
        </div>
        <div class="flex text-[#0A2E65] gap-12 border-b py-3 px-4 mx-auto">
          <p class="font-bold w-1/2">Beneficiary Bank:</p>
          <p class="w-1/2">Access Bank</p>
        </div>
        <div class="flex text-[#0A2E65] gap-12 border-b py-3 px-4 mx-auto">
          <p class="font-bold w-1/2">Phone Number:</p>
          <p class="w-1/2">09028484932</p>
        </div>
      </div>
        <button
        class="float-right rounded-md my-8 py-2 w-1/6 text-white font-bold bg-[#0098DA]"
      >
        Send
      </button>
    </div>
    
  </div>
</template>

<script>
import StatusButton from "../components/StatusButton.vue";
export default { components: { StatusButton } };
</script>

<style lang="scss" scoped></style>
