<script setup>
import { RouterLink, RouterView } from 'vue-router';
import Button from '@/components/base/button/Button.vue';
import Header from '@/components/layout/Header.vue';
</script>

<template>
    <Header />
    <div class="slidebar">SlideBar</div>
    <div class="main-content">Main</div>
</template>

<style scoped>
.slidebar {
    width: 200px;
    height: calc(100vh - 56px);
    float: left;
    background-color: aquamarine;
}

.main-content {
    width: calc(100% - 200px);
    height: calc(100vh - 56px);
    background-color: blueviolet;
    float: left;
    padding: 24px 24px 48px 24px;
    box-sizing: border-box;
}
</style>
