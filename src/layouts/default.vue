<template>
  <div data-theme="cupcake" class="min-h-screen">
    <div class="max-w-2xl mx-auto px-4 py-2 prose">
      <!-- <nav class="flex gap-4">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </nav> -->

      <div class="navbar bg-base-100">
        <div class="flex-1">
          <a class="btn btn-ghost normal-case text-xl">LOGO</a>
        </div>
        <div class="flex-none">
          <ul class="menu menu-horizontal p-0">
            <li><router-link to="/">Home</router-link></li>
            <li><router-link to="/about">About</router-link></li>
            <li>
              <button class="btn btn-primary">
                <router-link to="/subscribe">subscribe</router-link>
              </button>
            </li>
          </ul>
        </div>
      </div>

      <!-- PAGE CONTENT -->
      <slot />
      <!-- PAGE CONTENT -->
    </div>
  </div>
</template>

<style>
@import '~/assets/base.css';
</style>
