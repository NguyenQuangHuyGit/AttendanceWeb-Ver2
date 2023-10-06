<template>
    <button v-bind="$attrs">
        <span>{{ text }}</span>
    </button>
</template>

<script setup>
const props = defineProps({
    text: {
        type: String,
        required: true
    }
});
</script>

<style src="./button.css"></style>
