<script setup>
    import { ref } from 'vue'

    // Add code here
    import img from '/assets/me.png';
    const width = '200';
    const height = '200px';


</script>

<template>

    <!-- Add code here -->
    <img v-bind:src="img" :width="width" :height="height">
</template>
