<template>
    <div>
<HeaderComponent />
<ul>
    <li>home</li>
    <li><NuxtLink to="/products">products</NuxtLink></li>
    <li @click="$router.push('/products/pushdeneme')">id</li>
</ul>
    </div>
</template>

<script setup lang="ts">

</script>

