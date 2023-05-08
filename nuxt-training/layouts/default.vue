<template>
  <div>
    <ul>
      <li><NuxtLink to="/">home</NuxtLink></li>
      <li><NuxtLink to="/products">products</NuxtLink></li>
      <li><NuxtLink to="/products/pushdeneme"> id</NuxtLink></li>
    </ul>
  </div>

  <!-- output the pages content here -->
  <div>
    <slot />
  </div>

  <footer>
    <div
      style="
        background-color: rgba(81, 7, 19, 0.75);
        color: rgb(255, 255, 255);
        display: flex;
        justify-content: center;
      "
    >
      This is footer
    </div>
  </footer>
</template>
<style scoped>
.router-link-exact-active {
  color: brown;
  font-size: large;
  font-weight: bold;
}
</style>
