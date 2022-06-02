<template>
  <h1>Home View</h1>
  <p>
    <b>Counter: </b> {{ counterStore.counter }}
  </p>
  <p>
    <b>Number of changes: </b> {{ counterStore.numberOfChanges }}
  </p>
</template>

<script lang="ts" setup>
import { useCounterStore } from '../stores/counter'

const counterStore = useCounterStore()

</script>