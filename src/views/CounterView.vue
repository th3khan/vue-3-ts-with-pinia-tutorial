<template>
  <h1>Counter view</h1>
  <button @click="counterStore.increment(1)">+1</button>
  <button @click="counterStore.increment(2)">+2</button>
  <button @click="counterStore.increment(5)">+5</button>
</template>

<script lang="ts" setup>

import { useCounterStore } from '../stores/counter'

const counterStore = useCounterStore()

</script>