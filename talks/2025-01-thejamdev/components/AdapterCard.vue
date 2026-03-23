<script setup lang="ts">
defineProps<{
  name: string;
}>();
</script>

<template>
  <div class="flex flex-col items-center">
    <div class="size-16 bg-zinc-900 p-4 rounded-full border border-zinc-600 flex justify-center items-center">
      <slot />
    </div>
    <div>{{ name }}</div>
  </div>
</template>
