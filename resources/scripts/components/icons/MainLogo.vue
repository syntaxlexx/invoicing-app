<template>
  <img alt="AceLords Logo" src="https://x43mph8mpu.ufs.sh/f/4rTpTvA7QqKAHhqONcVKB1bD9CUPmQjcN3qyuY6pael4IVLR" class="h-28 w-auto object-contain" />
</template>

<script setup>

import {ref} from 'vue'

const props = defineProps({
  darkColor: {
    type: String,
    default: 'rgba(var(--color-primary-500), var(--tw-text-opacity))',
  },
  lightColor: {
    type: String,
    default: 'rgba(var(--color-primary-400), var(--tw-text-opacity))',
  },
})

</script>
