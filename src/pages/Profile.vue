<template>
<div>
    <h1 class="mb-9 px-12 pt-12 text-[#3C3C3B] font-semibold text-2xl">{{BreadcrumbTitle}}/~</h1>
    <div class="flex mt-20 w-full gap-12 md:gap-24 p-4 md:p-12">
        
        <img class="w-40 h-40 rounded-lg " src="../assets/courage 1.png" alt="">
        <div class="flex flex-col w-1/3">
            <h2 class="font-bold text-2xl md:text-3xl text-[#0A2E65] mb-2">Courage Coraigei</h2>
            <h3 class="text-[#6C82A3] text-sm md:text-lg mb-6">courage@gmail.com</h3>
            <p class="text-[#6C82A3] text-base md:text-2xl mb-3 font-bold">Loan Officer</p>
            <Button class="text-white text-xs gap-1 rounded-sm bg-[#0098DA] items-center px-4 py-2 w-full flex md:w-2/3 lg:w-1/3">
                <i><img src="../assets/icons/edit.svg" alt=""></i>
                Edit Profile
            </Button>
        </div>
    </div>
</div>
    
</template>

<script>
    export default {
        props:['BreadcrumbTitle']
    }
</script>

<style lang="scss" scoped>

</style>