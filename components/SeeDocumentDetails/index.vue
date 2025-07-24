<template>
    <nuxt-link :to="actionUrl"
     class="self-end bg-[#11B0C8] flex gap-2 py-[6px] pl-1 pr-2 rounded-[32px] text-sm items-center"
        target="_blank" rel="noopener">
          <IconsInfo/>
          Saiba mais
        </nuxt-link>
</template>

<script setup>
const props = defineProps({
actionUrl: String
})
</script>