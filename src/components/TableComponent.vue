<template>
    <h1>YABL</h1>
    <table  class="table-fixed w-full">
        <thead class="border-b" v-for="(column,index) in columns" :key="index">
            <tr>
                <th class="px-4 py-2">{{column}}</th>
            </tr>
        </thead>
        <tbody>
            <tr class="border-b py-10" v-for="(item,index) in items" :key="index">
                <td class="px-4 py-2 text-sm" v-for="(index,indexColumn) in items" :key="indexColumn">            
                   {{item[column]}}</td>
            </tr>
        </tbody>
    </table>
</template>

<script >
   const items=[
        {
            'id':'1',
            'Beneficiary Name': 'Musa John',
            'Ammount': '₦ 100,200,000.30',
            'Account Number': '2020599742',
            'Bank': 'UBA',
            'Phone Number': '07064394653'
        },
        {
            'id':'2',
            'Beneficiary Name': 'Musa John',
            'Ammount': '₦ 100,200,000.30',
            'Account Number': '2020599742',
            'Bank': 'UBA',
            'Phone Number': '07064394653'
        },
        {
            'id':'3',
            'Beneficiary Name': 'Musa John',
            'Ammount': '₦ 100,200,000.30',
            'Account Number': '2020599742',
            'Bank': 'UBA',
            'Phone Number': '07064394653'
      },
    ]
    const columns= [ 'id', 'Beneficiary Name', 'Ammount', 'Account Number','Bank','Phone Number']

    export default {
        name:"TableComponent",

    }
</script>

<style lang="sass" scoped>

</style>