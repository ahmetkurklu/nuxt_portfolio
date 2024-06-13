<template>
  <div>
    <header>
      <nav class="container mx-auto flex justify-between p-4">
        <NuxtLink to="/" class="font-bold">Portfolio</NuxtLink>
        <ul class="flex gap-4">
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/projects">Projects</NuxtLink></li>
        </ul>
      </nav>
    </header>

    <div class="container mx-auto p-4">
      <slot />
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style>

</style>