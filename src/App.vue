<script setup lang="ts">
import { useDark, useToggle } from '@vueuse/core'
const isDark = useDark()
const toggleDark = useToggle(isDark)
</script>

<template>
  <div>
    <el-button @click="toggleDark">dark</el-button>
  </div>
</template>

<style scoped>
</style>
