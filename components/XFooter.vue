<script lang="ts" setup>
withDefaults(defineProps<{
  version: string
}>(), {
  version: '1.0',
})
</script>

<template>
  <div class="footer max-w-[1080px] mx-auto flex gap-2 text-xs my-4 px-2 md:px-0 pb-4 text-gray-400 justify-between md:justify-normal relative">
    <span class="">
    </span>
    <span class="mx-1">•</span>
    <a target="_blank" href="https://makifx.com">MAKI分享</a>
  </div>
</template>

<style></style>
