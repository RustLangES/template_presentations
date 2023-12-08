<script setup lang="ts">
const props = withDefaults(
  defineProps<{
    text: string
  }>(),
  {
    text: '',
  },
)
</script>

<template>
    <div class="flex gap-2 flex-row items-center">
        <slot />
        <span>{{ props.text }}</span>
    </div>
</template>
