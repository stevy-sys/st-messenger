<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/"> Home </RouterLink>
        <RouterLink to="/profile"> Profile </RouterLink>
        <RouterLink to="/about"> About </RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
.wrapper {
  display: flex;
  justify-content: space-around;
}
</style>
