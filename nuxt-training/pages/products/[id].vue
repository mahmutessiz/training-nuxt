<template>
    <section>
        <div>route param {{ id }}</div>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum
            facilis quidem necessitatibus facere natus fuga nisi iste ipsum
            pariatur. Molestias laudantium porro consequuntur adipisci! Dicta
            eaque eligendi quibusdam aperiam amet facere accusantium error
            magnam ipsum fuga enim cum earum aliquid totam temporibus, rerum
            voluptatum voluptates nemo exercitationem voluptas modi qui.
        </p>
    </section>
</template>

<script setup>
const { id } = useRoute().params;
</script>
