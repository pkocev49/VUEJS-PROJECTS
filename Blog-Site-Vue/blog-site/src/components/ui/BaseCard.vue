<template>
  <div class="card">
    <slot></slot>
  </div>
</template>

<style scoped>
.card {
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  padding: 36px;
  margin: 32px auto;
  max-width: 640px;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
