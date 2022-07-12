<template>
    <div class="flex flex-col items-center rounded-lg bg-white w-4/5 h-72">
        <h2 class="text-[#0A2E65] text-2xl font-bold">Status</h2>
        <div>

        </div>
        <StatusButton text="Send"/>
    </div>
</template>

<script>
import StatusButton from '../components/StatusButton.vue';
    export default {
    components: { StatusButton }
}
</script>

<style lang="scss" scoped>

</style>