<script setup>
import { computed } from "vue";

const icons = import.meta.glob("/src/assets/icons/*.svg", { eager: true });

const props = defineProps({
  name: { type: String, required: true },
});

const iconComponent = computed(() => {
  const entries = Object.entries(icons);
  const match = entries.find(([key]) => {
    const fileName = key.split("/").pop()?.replace(".svg", "");
    return fileName === props.name;
  });
  if (!match) {
    console.warn(`Icon not found: ${props.name}`);
    return null;
  }
  return match[1].default || match[1];
});
</script>

<template>
  <component v-if="iconComponent" :is="iconComponent" v-bind="$attrs" />
</template>
