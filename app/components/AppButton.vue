<script setup>
defineProps({
    label: {
        type: String,
        required: true
    },
    color: {
        type: String,
        default: '#2563eb'
    }
})
</script>

<template>
    <button class="custom-btn" :style="{ backgroundColor: color }">
        {{ label }}
    </button>
</template>

<style scoped>
.custom-btn {
    color: white;
    border: none;
    padding: 10px 16px;
    border-radius: 6px;
    cursor: pointer;
    font-weight: bold;
    font-size: 0.9rem;
}
.custom-btn:hover {
    opacity: 0.9;
}
</style>