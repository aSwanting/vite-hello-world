<script setup>
import { ref } from 'vue'
</script>

<template>
    <div class="hero">
        <h1>VUE HERO</h1>
    </div>
</template>

<style scoped>
.hero {
    height: 400px;
    background: url(../assets/hero.jpg);
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 48px;
    text-align: center;
    color: white;
    padding: 50px;
    margin-bottom: 50px;
}
</style> 