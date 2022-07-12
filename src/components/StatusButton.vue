<template>
    <button class="bg-[#0098DA] rounded py-2 px-4 text-white text-sm  text-center">
        {{text}}
    </button>
</template>

<script>
    export default{
        name: "StatusButton",
        props:{
            text:{
                text:String,
            },
            color:{
                text: String
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>