<template>
  <div>
    <!-- <div class="flex gap-8">
      
      <div class="flex gap-2 items-center focus:text-[#0098DA]">
        <i><img src="../assets/icons/Single.svg" alt="" /></i>
        <p>Single Transfer</p>
      </div>
      <div class="flex gap-2 items-center focus:text-[#0098DA]">
        <i><img src="../assets/icons/Batch.svg" alt="" /></i>
        <p>Batch Transfer</p>
      </div>
    </div> -->

    <!-- //Tab navigation -->
    <ul class="flex flex-wrap text-sm font-medium text-center text-gray-500 border-b border-gray-200 dark:border-gray-700 dark:text-gray-400">
    <li class="mr-2 flex bg-gray-100 rounded-t-lg ">
      <div class="flex items-center"> 
        <i><img src="../assets/icons/Single.svg" alt=""></i>
        <a href="#" aria-current="page" class="inline-block p-4 text-[#0098DA] active  ">Single Transfer</a>
      </div>
      
    </li>
    <li class="mr-2">
      <i><img src="../assets/icons/Batch.svg" alt=""></i>
        <a href="#" class="inline-block p-4 rounded-t-lg hover:text-gray-600 hover:bg-gray-50 dark:hover:bg-gray-800 dark:hover:text-gray-300">Batch Transfer</a>
    </li>
    
</ul>

    <div class="mx-auto pt-9 ">
      <div class="md:flex  w-full md:items-start border-b ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0 md:w-1/2">
          <h2 class="text-[#0A2E65] font-bold md:text-lg mb-1 ">
            Beneficiary Name
          </h2>
          <p class="text-[#6C82A3] text-sm hidden md:block">Surnname First</p>
        </div>
        <div class="flex w-full gap-12 h-fit ml-4 md:ml-0 md:w-1/2">
          <div class="">
            <form class="h-auto" action="">
              <div class="flex flex-col w-full align-top mb-10">
                <label class="text-xs text-left mb-2 text-[#6C82A3] hidden md:block" for="Name">
                  Beneficiary Name
                </label>
                <input
                  class="bg-[#F5F6FA] md:h-16 md:w-80 px-2 md:px-8 text-[#0A2E65] border rounded-md"
                  type="text"
                  placeholder="Isifeh Kizito"
                />
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div class="mx-auto pt-9">
      <div class="md:flex w-full items-start border-b ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0  w-1/2">
          <h2 class="text-[#0A2E65] font-bold md:text-lg mb-1">
            Account Number
          </h2>
          <p class="text-[#6C82A3] text-sm hidden md:block">Beneficiary Account Number</p>
        </div>
        <div class="flex gap-12 h-fit w-1/2">
          <div class="">
            <form class="h-auto" action="">
              <div class="flex flex-col w-full align-top mb-10">
                <label class="text-xs text-left mb-2 text-[#6C82A3] hidden md:block" for="Name">
                  Beneficiary Account Number
                </label>
                <input
                  class="bg-[#F5F6FA] md:h-16 md:w-80 px-2 md:px-8 text-[#0A2E65] border rounded-md"
                  type="text"
                  placeholder="2020599742"
                />
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div class="mx-auto pt-9">
      <div class="md:flex w-full items-start border-b ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0  w-1/2">
          <h2 class="text-[#0A2E65] font-bold md:text-lg mb-1">
            Ammount
          </h2>
          <p class="text-[#6C82A3] text-sm hidden md:block">...</p>
        </div>
        <div class="flex gap-12 h-fit w-1/2">
          <div class="">
            <form class="h-auto" action="">
              <div class="flex flex-col w-full align-top mb-10">
                <label class="text-xs text-left mb-2 text-[#6C82A3] hidden md:block" for="Name">
                  Total Amount
                </label>
                <input
                  class="bg-[#F5F6FA] md:h-16 md:w-80 px-2 md:px-8 text-[#0A2E65] border rounded-md"
                  type="text"
                  placeholder="N200,000"
                />
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div class="mx-auto pt-9 ">
      <div class="md:flex w-full items-start border-b ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0 w-1/2">
          <h2 class="text-[#0A2E65] font-bold md:text-lg mb-1">
            Bank
          </h2>
          <p class="text-[#6C82A3] text-sm hidden md:block">Beneficiary Bank</p>
        </div>
        <div class="flex gap-12 h-fit w-1/2">
          <div class="">
            <form class="h-auto" action="">
              <div class="flex flex-col w-full align-top mb-10">
               
                <input
                  class="bg-[#F5F6FA] md:h-16 md:w-80 px-2 md:px-8 text-[#0A2E65] border rounded-md"
                  type="text"
                  placeholder="Select Beneficiary Bank"
                />
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div class="mx-auto pt-9">
      <div class="md:flex w-full items-start border-b ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0  w-1/2">
          <h2 class="text-[#0A2E65] font-bold md:text-lg mb-1">
            Phone Number
          </h2>
          <p class="text-[#6C82A3] text-sm hidden md:block">...</p>
        </div>
        <div class="flex gap-12 h-fit w-1/2">
          <div class="">
            <form class="h-auto" action="">
              <div class="flex flex-col w-full align-top mb-10">
               <label class="text-xs text-left mb-2 text-[#6C82A3] hidden md:block" for="Name">
                  Beneficiary Phone Number
                </label>
                <input
                  class="bg-[#F5F6FA] md:h-16 md:w-80 px-2 md:px-8 text-[#0A2E65] border rounded-md"
                  type="text"
                  placeholder="0904785483291"
                />
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div class="mx-auto pt-9">
      <div class="md:flex w-full items-start border-b ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0  md:w-1/2">
          <h2 class="text-[#0A2E65] font-bold text-lg mb-1">
            Remark
          </h2>
          <p class="text-[#6C82A3] text-sm hidden md:block">...</p>
        </div>
        <div class="flex gap-12 h-fit md:w-1/2">
          <div class="">
            <form class="h-auto" action="">
              <div class="flex flex-col w-full align-top mb-10">
               <label class="text-xs text-left mb-2 text-[#6C82A3] hidden md:block" for="Name">
                  Enter Remark
                </label>
                <textarea class="bg-[#F5F6FA] md:h-16 w-full md:w-80 md:px-8 text-[#0A2E65] border rounded-md"
                  type="text"
                  placeholder="Kindly approve, documentation
is complete." name="" id="" cols="30" rows="10"></textarea>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <StatusButton class="my-12 ml-4 md:ml-0 bg-[#0098DA]" text="Preview"/>
  </div>
</template>

<script>
import StatusButton from '../components/StatusButton.vue';
export default { components: { StatusButton } };
</script>

<style lang="scss" scoped></style>
