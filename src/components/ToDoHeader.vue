<template>
    <header>
        <nav class="container">
            <div class="branding">
                <img src="../assets/Vue_Logo_Black.png" alt="picture" >
                <h1>vue to do </h1>
            </div>
            <div class="nav-routes">
                <RouterLink  to="/"> Home</RouterLink>
                <RouterLink  to="/"> About</RouterLink>
            </div>
        </nav>
    </header>
</template>

<script setup>

import {RouterLink} from 'vue-router';

</script>

<style lang="scss" scoped>

</style>