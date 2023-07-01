<script setup lang="ts">
withDefaults(defineProps<{
  label?: string
}>(), {
  label: 'Button'
})
</script>

<template>
  <button type="button" class="n-button">
    {{ label }}
  </button>
</template>

<style>
@import url('./Button.css')
</style>
