<script setup lang="ts">

</script>
<template>
  Hello index page:
  <div class="flex flex-col gap-2">
    <NuxtLink to="/test1">Test1</NuxtLink>
    <NuxtLink to="/test2">Test2</NuxtLink>
    <NuxtLink to="/test3">Test3</NuxtLink>
    <NuxtLink to="/test4">Test4</NuxtLink>
    <NuxtLink to="/test5">Test5</NuxtLink>
    <NuxtLink to="/test6">Test6</NuxtLink>
    <NuxtLink to="/test7">Test7</NuxtLink>
    <NuxtLink to="/test8">Test8</NuxtLink>
    <NuxtLink to="/test9">Test9</NuxtLink>
    <NuxtLink to="/test10">Test10</NuxtLink>
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
