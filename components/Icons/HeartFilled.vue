<template>
    <svg 
    :width="width" 
    :height="height" 
    viewBox="0 0 48 48" 
    fill="none" 
    xmlns="http://www.w3.org/2000/svg">
    <path d="M45 17.625C45 30.75 25.5394 41.3738 24.7106 41.8125C24.4922 41.93 24.248 41.9915 24 41.9915C23.752 41.9915 23.5078 41.93 23.2894 41.8125C22.4606 41.3738 3 30.75 3 17.625C3.00347 14.5429 4.22936 11.5881 6.40872 9.40872C8.58808 7.22936 11.5429 6.00347 14.625 6C18.4969 6 21.8869 7.665 24 10.4794C26.1131 7.665 29.5031 6 33.375 6C36.4571 6.00347 39.4119 7.22936 41.5913 9.40872C43.7706 11.5881 44.9965 14.5429 45 17.625Z" 
    :fill="color"/>
</svg>


</template>

<script setup lang="ts">
const {
    width= 48, 
    height= 48, 
    color= "#11B0C8"
} = defineProps<{
    width?: number, 
    height?: number, 
    color?: string
}>();
</script>