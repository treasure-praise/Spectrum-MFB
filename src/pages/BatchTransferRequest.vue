<template>
  <div>
    <div class="flex gap-8">
      <div class="flex gap-2 items-center focus:text-[#0098DA]">
        <i><img src="../assets/icons/Single.svg" alt="" /></i>
        <p>Single Transfer</p>
      </div>
      <div class="flex gap-2 items-center focus:text-[#0098DA]">
        <i><img src="../assets/icons/Batch.svg" alt="" /></i>
        <p>Batch Transfer</p>
      </div>
    </div>
    <div class="mx-auto pt-9">
      <div class="md:flex w-full items-start border-b ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0 md:w-1/2 w-full">
          <h2 class="text-[#0A2E65] font-bold md:text-lg mb-1">
            Beneficiaries Names
          </h2>
          <p class="text-[#6C82A3] text-sm hidden md:block">Surnname First</p>
        </div>
        <div class="flex gap-12 h-fit md:w-1/2 w-full">
          <div class="">
            <form class="h-auto" action="">
              <div class="flex flex-col w-full align-top mb-10">
                <label class="text-xs text-left mb-2 text-[#6C82A3] hidden md:block" for="Name">
                  Beneficiary Name
                </label>
                <input
                  class="bg-[#F5F6FA] md:h-16 md:w-80 w-full px-2 md:px-8 text-[#0A2E65] border rounded-md"
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
                  class="bg-[#F5F6FA] md:h-16 md:w-80 md:px-8 px-2 text-[#0A2E65] border rounded-md"
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
        <div class="flex flex-col mt-4 ml-4 md:ml-0 w-1/2">
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
    <div class="mx-auto pt-9">
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
      <div class="md:flex w-full items-start ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0 w-1/2">
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
    <StatusButton class="my-12 bg-[#0098DA]" text="Add"/>

            </form>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Table Component goes here -->
    <div class="relative break-words   block w-full overflow-x-auto">
       <table class="table-fixed w-full rounded-lg bg-white my-16">
        <thead class="border-b m-12">
            <tr class="">

                <th class="px-4 py-2 ">
                    <input type="checkbox" name="" id="">
                </th>
                <th class="px-4 py-2 ">Beneficiary Name</th>
                <th class="px-4 py-2">Amount</th>
                <th class="px-4 py-2">Account Number</th>
                <th class="px-4 py-2">Bank</th>
                <th class="px-4 py-2">Phone Number</th>
            </tr>   
        </thead>
        <tbody class="my-6 ">
            <tr class="border-b py-10 my-6">
                <td class="px-4 py-5 text-sm text-center">
                    <input type="checkbox" name="" id="">
                </td>
                    <td>
                        <div class=" px-4 py-5 flex flex-col  text-center">
                            <p class="text-sm font-bold">Musa John</p>
                        </div>
                    </td>
                    <td class="px-4 py-5 text-sm text-center" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-5 text-sm text-center">2020599742</td>
                   <td class=" px-4 py-5 text-sm text-center">UBA</td>
                   <td class=" px-4 py-5 text-sm text-center">07064394653</td>
                
            </tr>
            <tr class="border-b py-10 my-6">
                <td class="px-4 py-5 text-sm text-center">
                    <input type="checkbox" name="" id="">
                </td>
                    <td>
                        <div class=" px-4 py-5 flex flex-col  text-center">
                            <p class="text-sm font-bold">Musa John</p>
                        </div>
                    </td>
                    <td class="px-4 py-5 text-sm text-center" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-5 text-sm text-center">2020599742</td>
                   <td class=" px-4 py-5 text-sm text-center">UBA</td>
                   <td class=" px-4 py-5 text-sm text-center">07064394653</td>
                
            </tr>
            <tr class="border-b py-10 my-6">
                <td class="px-4 py-5 text-sm text-center">
                    <input type="checkbox" name="" id="">
                </td>
                    <td>
                        <div class=" px-4 py-5 flex flex-col  text-center">
                            <p class="text-sm font-bold">Musa John</p>
                        </div>
                    </td>
                    <td class="px-4 py-5 text-sm text-center" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-5 text-sm text-center">2020599742</td>
                   <td class=" px-4 py-5 text-sm text-center">UBA</td>
                   <td class=" px-4 py-5 text-sm text-center">07064394653</td>
                
            </tr>
            <tr class="border-b py-10 my-6">
                <td class="px-4 py-5 text-sm text-center">
                    <input type="checkbox" name="" id="">
                </td>
                    <td>
                        <div class=" px-4 py-5 flex flex-col  text-center">
                            <p class="text-sm font-bold">Musa John</p>
                        </div>
                    </td>
                    <td class="px-4 py-5 text-sm text-center" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-5 text-sm text-center">2020599742</td>
                   <td class=" px-4 py-5 text-sm text-center">UBA</td>
                   <td class=" px-4 py-5 text-sm text-center">07064394653</td>
                
            </tr>
            <tr class="border-b py-10 my-6">
                <td class="px-4 py-5 text-sm text-center">
                    <input type="checkbox" name="" id="">
                </td>
                    <td>
                        <div class=" px-4 py-5 flex flex-col  text-center">
                            <p class="text-sm font-bold">Musa John</p>
                        </div>
                    </td>
                    <td class="px-4 py-5 text-sm text-center" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-5 text-sm text-center">2020599742</td>
                   <td class=" px-4 py-5 text-sm text-center">UBA</td>
                   <td class=" px-4 py-5 text-sm text-center">07064394653</td>
                
            </tr>
            <tr class="border-b py-10 my-6">
                <td class="px-4 py-5 text-sm text-center">
                    <input type="checkbox" name="" id="">
                </td>
                    <td>
                        <div class=" px-4 py-5 flex flex-col  text-center">
                            <p class="text-sm font-bold">Musa John</p>
                        </div>
                    </td>
                    <td class="px-4 py-5 text-sm text-center" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-5 text-sm text-center">2020599742</td>
                   <td class=" px-4 py-5 text-sm text-center">UBA</td>
                   <td class=" px-4 py-5 text-sm text-center">07064394653</td>
                
            </tr>
        </tbody>
    </table>
    </div>
    

     <div class="mx-auto pt-9">
      <div class="md:flex w-full items-start border-b ">
        <div class="flex flex-col mt-4 ml-4 md:ml-0 md:w-1/2">
          <h2 class="text-[#0A2E65] font-bold text-lg mb-1">
            Remark
          </h2>
          <p class="text-[#6C82A3] text-sm hidden md:block">...</p>
        </div>
        <div class="flex md:gap-12 h-fit md:w-1/2 ">
          <div class="">
            <form class="h-auto" action="">
              <div class="flex flex-col w-full align-top mb-10">
               <label class="text-xs text-left mb-2 text-[#6C82A3] hidden md:block" for="Name">
                  Enter Remark
                </label>
                <textarea class="bg-[#F5F6FA] md:h-16 md:w-80 w-80 px-2 md:px-8 text-[#0A2E65] border rounded-md"
                  type="text"
                  placeholder="Kindly approve, documentation
is complete." name="" id="" cols="30" rows="10"></textarea>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <StatusButton class="my-12 ml-4 bg-[#0098DA]" text="Preview"/>
  </div>
</template>

<script>
import StatusButton from '../components/StatusButton.vue';
export default { components: { StatusButton } };
</script>

<style lang="scss" scoped></style>
