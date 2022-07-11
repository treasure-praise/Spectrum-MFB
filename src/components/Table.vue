<template>
    <table class="table-fixed w-full">
        <thead class="border-b">
            <tr >
                <th class="px-4 py-2">Account Details</th>
                <th class="px-4 py-2">Amount</th>
                <th class="px-4 py-2">Phone Number</th>
                <th class="px-4 py-2">Transfer Type</th>
                <th class="px-4 py-2">Created By</th>
                <th class="px-4 py-2">Initiated By</th>
                <th class="px-4 py-2">Status</th>
                <th class="px-4 py-2">Remark</th>
            </tr>   
        </thead>
        <tbody>
            <tr class="border-b py-10">
                    <td>
                        <div class=" px-4 py-2flex flex-col">
                            <p class="text-sm font-bold">Musa John</p>
                            <span class="text-xs">2056317233 (Uba Bank)</span>
                        </div>
                    </td>
                    <td class="px-4 py-2 text-sm" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-2 text-sm">07064394653</td>
                    <td class="px-4 py-2">
                        <div class="flex items-center gap-2">
                            <p class="text-sm font-bold">Single</p>
                            <span class="text-sm"><i><img src="../assets/icons/Single.svg" alt="" srcset=""></i></span>
                        </div>
                    </td>
                    <td class="text-sm px-4 py-2">13 Jan, 2022 12:01am </td>
                    <td class="text-sm px-4 py-2">Jude Ibrahim</td>
                    <td class="px-4 py-2 text-center"><button class="bg-[#0098DA] rounded py-1 px-2 text-white text-sm  text-center">Single</button></td>
                    <td class="text-sm px-4 py-2 text-center">Treated</td>
            </tr>
             <tr class="border-b">
                    <td>
                        <div class=" px-4 py-2flex flex-col">
                            <p class="text-sm font-bold">Musa, Chizoba, John</p>
                            <span class="text-xs">2056317233, 5768940324,...</span>
                        </div>
                    </td>
                    <td class="px-4 py-2 text-sm" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-2 text-sm text-center">---</td>
                    <td class="px-4 py-2">
                        <div class="flex items-center gap-2">
                            <p class="text-sm font-bold">Batch</p>
                            <span class="text-sm"><i><img src="../assets/icons/batch.svg" alt="" srcset=""></i></span>
                        </div>
                    </td>
                    <td class="text-sm px-4 py-2">13 Jan, 2022 12:01am </td>
                    <td class="text-sm px-4 py-2">Courage Musa</td>
                    <!-- <td>
                        <StatusButton msg="Pending"/>
                    </td> -->
                    <td class="px-4 py-2 text-center"><button class="bg-[#FEDB6E] rounded py-1 px-2 text-white text-sm  text-center">Pending</button></td>
                    <td class="text-sm px-4 py-2 text-center">Awaiting Override</td>
            </tr>
            <tr class="border-b">
                    <td>
                        <div class=" px-4 py-2flex flex-col">
                            <p class="text-sm font-bold">Musa John</p>
                            <span class="text-xs">2056317233 (Uba Bank)</span>
                        </div>
                    </td>
                    <td class="px-4 py-2 text-sm" >₦ 100,200,000.30</td>
                    <td class=" px-4 py-2 text-sm text-center">---</td>
                    <td class="px-4 py-2">
                        <div class="flex items-center gap-2">
                            <p class="text-sm font-bold">Batch</p>
                            <span class="text-sm"><i><img src="../assets/icons/batch.svg" alt="" srcset=""></i></span>
                        </div>
                    </td>
                    <td class="text-sm px-4 py-2">13 Jan, 2022 12:01am </td>
                    <td class="text-sm px-4 py-2">Elizabeth Bello</td>
                    <!-- <td>
                        <StatusButton msg="Pending"/>
                    </td> -->
                    <td class="px-4 py-2 text-center"><button class="bg-[#ED3237] rounded py-1 px-2 text-white text-sm  text-center">Rejected</button></td>
                    <td class="text-sm px-4 py-2 text-center">Incomplete Profile</td>
            </tr>
        </tbody>
    </table>
</template>

<script>
    
         let items = [
        {
            'id':'1',
            'accName': 'Musa John',
            'accNumber': '2056317233 ',
            'bankName':'(Uba Bank)',
            'ammount':'₦ 100,200,000.30',
            'phoneNumber':'07064394653',
            'transferType':'Batch',
            'createdBy': '13 Jan, 2022 12:01am',
            'initiatedBy':'Jude Ibrahim',
            'status':["success","pending", "rejected"],
            'remark':['treated','Awaiting Overide','Incomplete Profile']
        },
        {
            'id':'1',
            'accName': 'Musa John',
            'accNumber': '2056317233 ',
            'bankName':'(Uba Bank)',
            'ammount':'₦ 100,200,000.30',
            'phoneNumber':'07064394653',
            'transferType':'Batch',
            'createdBy': '13 Jan, 2022 12:01am',
            'initiatedBy':'Jude Ibrahim',
            'status':["success","pending", "rejected"],
            'remark':['treated','Awaiting Overide','Incomplete Profile']
        }
    ]
    let columns  = [ 'Account Details', 'Amount', 'Phone Number', 'Transfer Type', 'Created By', 'Initiated By', 'Status', 'Remark']

   
</script>

<style lang="scss" scoped>

</style>