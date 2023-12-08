<script setup lang="ts">
import { computed } from 'vue'
import { toArray } from '@antfu/utils'

const props = withDefaults(
  defineProps<{
    listClass?: string | string[]
  }>(),
  {
    listClass: '',
  },
)

const classes = computed(() => {
  return [
    'card', 'flex', 'px-6', 'py-4', 'items-center',
    ...toArray(props.listClass || []),
  ]
})
</script>

<template>
    <div :class="classes">
        <slot />
    </div>
</template>