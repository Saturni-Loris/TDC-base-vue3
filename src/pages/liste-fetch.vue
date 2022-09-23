<script setup>
const res = await fetch(/maisons.json)
const posts = await res.json()
</script>

<template>
  <div v-for="maison of maisons" class="p-3 pt-12">
    <card v-bind="maison" />
  </div>
</template>
