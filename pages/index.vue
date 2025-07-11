<script setup lang="ts">
const random = [
  Math.random(),
  Math.random(),
  Math.random(),
  Math.random(),
  Math.random(),
  Math.random(),
]
</script>
<template>
  Hello index page:
  <div class="flex flex-col gap-2">
    <NuxtLink
      v-for="i in random"
      :key="i"
      :to="`/${i}`"
    >
      Page random: {{ i }}
    </NuxtLink>
  </div>
</template>

<style>
.flex {
  display: flex;
}
.flex-col {
  flex-direction: column;
}
.gap-2 {
  gap: 1rem;
}
</style>
