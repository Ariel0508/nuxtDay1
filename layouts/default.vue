<script setup></script>
<template>
  <header>
    <ul class="list">
      <li><NuxtLink to="/">前台 home</NuxtLink></li>
      <li><NuxtLink to="/about">前台 about</NuxtLink></li>
      <li><NuxtLink to="/admin">前往後台 home</NuxtLink></li>
      <li><NuxtLink to="/admin/order">前往後台 order</NuxtLink></li>
    </ul>
  </header>
  <slot />
  <footer>前台模板的表尾</footer>
</template>
<style scoped></style>
