<script setup>
    import { ref } from 'vue'

    // Add code here
    const img = ref('/assets/me.png');
    const width = ref('200');
    const height = ref('200');

    const obj = ref({
        width: '200',
        height: '200',
        src: '/assets/me.png'
    });
    
</script>

<template>

    <!-- Add code here -->
    <img v-bind:src="img" :width="width" :height="height">
    <img v-bind="obj">
</template>
