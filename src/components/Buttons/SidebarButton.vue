<script setup lang="ts">
import { RouterLink } from "vue-router";

const props = defineProps<{
  path: string;
  label: string;
  icon?: string;
}>();
</script>

<template>
  <RouterLink
    :to="props.path"
    class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
  >
    <slot name="icon" /><span>{{ props.label }}</span></RouterLink
  >
</template>
