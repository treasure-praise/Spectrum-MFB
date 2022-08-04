<template>
  <div>
    <div class="">
        <button class=" float-right">
            <img  src="../assets/icons/close.svg" alt="" />
        </button>
        
        <h1 class="text-[#0A2E65] float-left mt-8 block text-4xl font-bold mb-20">Summary</h1>
    </div>
    
    
 

     <div class="py-14 px-4 md:flex mx-auto">
        <div class="flex flex-col w-full mb-8 md:mb-0 align-top">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Token">
              Token
            </label>
            <input
              class="bg-[#F5F6FA] text-[#0A2E65] border rounded-md md:h-16 md:w-80 md:px-8"
              type="text"
              placeholder="039408437"
            />
        </div>
        <div class="flex flex-col w-full mb-8 md:mb-0 align-top">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Remark">
              Enter Remark
            </label>
            <textarea class="bg-[#F5F6FA] text-[#0A2E65] border rounded-md h-16  px-8 md:h-16 md:w-80 md:px-8"
              type="text"
              placeholder="Approves" name="" id="" cols="30" rows="20"></textarea>
        </div>
    </div>
    <div>
        <h2 class="text-[#6C82A3] text-2xl px-4 pb-8 border-b">Audit Trails</h2>
        <div class="mt-8 md:flex px-4 gap-y-8 pb-12 flex-wrap">
            <div class="flex flex-col w-full md:w-1/2 mb-8 md:mb-0 align-top">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Created By">
              Created By
            </label>
            <input
              class="bg-[#F5F6FA] text-[#0A2E65] border rounded-md md:h-16 md:w-80 md:px-8"
              type="text"
              placeholder="Henry Ubi"
            />
            </div>
            <div class="flex flex-col w-full md:w-1/2 mb-8 md:mb-0 align-top">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for=" Date Created">
              Date Created
            </label>
            <input
              class="bg-[#F5F6FA] text-[#0A2E65] border rounded-md md:h-16 md:w-80 md:px-8"
              type="text"
              placeholder="06/07/22  10:20:17 am"
            />
            </div>
            <div class="flex flex-col w-full md:w-1/2 mb-8 md:mb-0  align-top">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for=" Last Modified by">
              Last Modified by
            </label>
            <input
              class="bg-[#F5F6FA] text-[#0A2E65] border rounded-md md:h-16 md:w-80 md:px-8"
              type="text"
              placeholder="Henry Ubi"
            />
            </div>
            <div class="flex flex-col w-full md:w-1/2 mb-8 md:mb-0 align-top">
            <label class="text-xs text-left mb-2 text-[#6C82A3]" for="Date Modified">
              Date Modified
            </label>
            <input
              class="bg-[#F5F6FA] text-[#0A2E65] border rounded-md md:h-16 md:w-80 md:px-8"
              type="text"
              placeholder="06/07/22  10:20:17 am"
            />
            </div>
        </div>
        <div class="flex px-4 gap-4">
            <StatusButton text="Reject" color="ED3237"/>
            <StatusButton text="Approve" color="ED3237"/>
        </div>
        
    </div>
  </div>
</template>

<script setup >
import StatusButton from '../components/StatusButton.vue';
import Table from '../components/Table.vue';
import TableComponent from '../components/TableComponent.vue';

</script>

<style scoped></style>
