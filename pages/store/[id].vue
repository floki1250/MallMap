<template>
    <div>
        <iframe :src="data[route.params.id].url" frameborder="0" class="w-full h-screen"></iframe>
    </div>
</template>

<script setup>
const route = useRoute();
const data = {
    14: {
        name: "Carrefour",
        url: "https://www.carrefour.tn/",
    },
};
</script>
