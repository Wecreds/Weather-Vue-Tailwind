<script setup>
import AsyncitCityView from '../components/AsyncitCityView.vue'
</script>
<template>
  <div>
    <Suspense>
      <AsyncitCityView/>
      <template #fallback>
        <p>Loading</p>
      </template>
    </Suspense>
  </div>
</template>
