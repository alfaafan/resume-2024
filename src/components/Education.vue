<script setup lang="ts">
defineProps<{
  education: 'Bachelor Degree'
}>()
</script>

<template>
  <div class="education">
    <h2>{{ education }}</h2>
    <p>Software Engineering</p>
    <p>Universitas Gadjah Mada</p>
  </div>
</template>

<style scoped>
h2 {
  font-size: 1.8rem;
  font-weight: 500;
  margin-bottom: 0.4rem;
  color: var(--color-heading);
}
</style>
