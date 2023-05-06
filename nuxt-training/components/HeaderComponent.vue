<template>
    <div>
        <nav>
            <ul>
                <li @click="clickAlert">home</li>
                <li>pricing</li>
                <li>about</li>
            </ul>
        </nav>
    </div>
</template>
<script setup lang="ts">

const clickAlert:any = ()=>{
    alert('this is warking')
}
</script>