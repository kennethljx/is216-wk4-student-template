<script setup>
    import { ref } from 'vue'

    // Add code here
    import img from '/assets/me.png';
    const width = '200';
    const height = '200px';

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
