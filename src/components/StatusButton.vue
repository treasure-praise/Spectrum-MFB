<template>
    <button class="bg-[#0098DA] rounded py-1 px-2 text-white text-sm  text-center " :class="[text === 'Pending'
                  ? 'bg-[#FEDB6E] text-black '
                  : 'bg-[#ED3237] text-white ',
                  ]">
        {{text}}
    </button>
</template>

<script>
    export default{
        name: "StatusButton",
        props:{
            text:String ,
            color: String
        } 
    }
</script>

<style lang="scss" scoped>

</style>