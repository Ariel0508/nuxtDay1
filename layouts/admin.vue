<script setup></script>
<template>
  <header>
    <ul class="list">
      <li><NuxtLink to="/">前往前台 home</NuxtLink></li>
      <li><NuxtLink to="/about">前往前台 about</NuxtLink></li>
      <li><NuxtLink to="/admin">後台 home</NuxtLink></li>
      <li><NuxtLink to="/admin/order">後台 order</NuxtLink></li>
    </ul>
  </header>
  <slot />
  <footer>後台模板的表尾</footer>
</template>
<style scoped></style>
