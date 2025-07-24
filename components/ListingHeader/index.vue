<template>
    <header class="flex gap-4 items-center p-2">
        <h2 class="font-bold text-2x1">{{title}}</h2>

        <button class="flex gap-2 p-1 pr-2 bg-[#313234] rounded-[32px]">
            <IconsSquaresFour/>
            Ver todos
        </button>
    </header>
</template>

<script setup>
const props = defineProps({
    title: String
})
</script>