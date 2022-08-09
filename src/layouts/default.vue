<template>
  <div data-theme="emerald" class="min-h-screen">
    <div class="max-w-2xl mx-auto px-4 py-2 prose">
      <nav class="flex gap-4">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </nav>

      <!-- PAGE CONTENT -->
      <slot />
      <!-- PAGE CONTENT -->
    </div>
  </div>
</template>

<style>
@import '~/assets/base.css';
</style>
