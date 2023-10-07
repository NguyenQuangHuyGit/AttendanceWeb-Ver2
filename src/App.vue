<script setup>
import { RouterLink, RouterView } from 'vue-router';
import Header from '@/components/layout/header/Header.vue';
import Slidebar from '@/components/layout/sidebar/Sidebar.vue';
import MainSection from '@/components/layout/main/Mainsection.vue';
</script>

<template>
    <Header />
    <Slidebar />
    <MainSection />
</template>
