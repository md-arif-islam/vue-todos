<script setup></script>

<template>
  <button @click="createTodo()">
    <slot></slot>
  </button>
</template>

<style lang="scss" scoped>
button {
  padding: 8px 16px;
  border: none;
}
</style>
