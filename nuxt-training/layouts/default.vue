<template>
    <div>
<ul>
    <li><NuxtLink to="/">home</NuxtLink> </li>
    <li><NuxtLink to="/products">products</NuxtLink></li>
    <li @click="$router.push('/products/pushdeneme')"> id</li>
</ul>
    </div>

    <!-- output the pages content here -->
    <div>
        <slot/>
    </div>
</template>
<style scoped>
.router-link-exact-active{
    color: brown;
    font-size: large;
    font-weight: bold;
}
</style>