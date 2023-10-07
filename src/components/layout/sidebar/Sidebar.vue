<script setup>
import SidebarItem from './SidebarItem.vue';
</script>
<template>
    <div class="sidebar">
        <div class="sidebar__top">
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
            <SidebarItem />
        </div>
        <div class="sidebar__bottom">
            <div class="sidebar__bottom--icon">
                <img src="@/assets/icon/arrowhead-left-outline.svg" alt="" />
            </div>
            <div class="sidebar__bottom--title"></div>
        </div>
    </div>
</template>

<style src="./sidebar.css"></style>
