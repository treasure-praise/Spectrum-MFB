<template>
  <div class="w-full h-auto  flex-col mx-4">
    <form action="" class="mx-4">
      <div class="border-b md:flex w-full ">
        <div class="flex flex-col  md:w-1/2 ">
          <h2 class="mt-4 font-bold text-lg text-[#0A2E65]">Name</h2>
          <span class="text-[#6C82A3]">...</span>
        </div>
        <div class="md:w-1/2">
          <div class="flex flex-col w-full align-top mb-10">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Name">
              Name
            </label>
            <input
              class="bg-[#F5F6FA] h-16 md:w-80 w-full px-8 text-[#0A2E65] border rounded-md"
              type="text"
              placeholder="lorem ispum"
            />
          </div>
        </div>
      </div>
      <div class="border-b md:flex w-full py-8">
        <div class="flex flex-col md:w-1/2">
          <h2 class="mt-4 font-bold text-lg text-[#0A2E65]">Email</h2>
          <span class="text-[#6C82A3]">...</span>
        </div>
        <div class="md:w-1/2">
          <div class="flex flex-col w-full align-top mb-10">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Email">
              Staff Email
            </label>
            <input
              class="bg-[#F5F6FA] h-16 md:w-80 w-full px-8 text-[#0A2E65] border rounded-md"
              type="text"
              placeholder="lorem@gmail.com"
            />
          </div>
        </div>
      </div>
      <div class="border-b md:flex w-full py-8">
        <div class="flex flex-col w-1/2">
          <h2 class="mt-4 font-bold text-lg text-[#0A2E65]">Role</h2>
          <span class="text-[#6C82A3]">...</span>
        </div>
        <div class="md:w-1/2">
          <div class="flex flex-col w-full align-top mb-10">
            <input
              class="bg-[#F5F6FA] h-16 md:w-80 w-full px-8 text-[#0A2E65] border rounded-md"
              type="text"
              placeholder="User Role"
            />
          </div>
        </div>
      </div>
      <div class="border-b md:flex w-full py-8">
        <div class="flex flex-col w-1/2">
          <h2 class="mt-4 font-bold text-lg text-[#0A2E65]">Branch</h2>
          <span class="text-[#6C82A3]">...</span>
        </div>
        <div class="md:w-1/2">
          <div class="flex flex-col w-full align-top mb-10">
            <input
              class="bg-[#F5F6FA] h-16 md:w-80 w-full px-8 text-[#0A2E65] border rounded-md"
              type="text"
              placeholder="Branch"
            />
          </div>
        </div>
      </div>
      <button class="bg-[#0098DA] rounded-md my-20 w-24 h-12 text-white" type="submit">
        Submit
      </button>
    </form>

   
  </div>
</template>

<script>


export default {
    components:{
      
    }
};
</script>

<style lang="scss" scoped></style>
