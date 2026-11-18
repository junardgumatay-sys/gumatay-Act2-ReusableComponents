<script setup>
defineProps({
    title: String,
    description: String
})
</script>

<template>
    <div class="info-card">
        <h3>{{ title }}</h3>
        <p>{{ description }}</p>
    </div>
</template>

<style scoped>
.info-card {
    background-color: #eff6ff;
    border-left: 5px solid rgb(235, 113, 75);
    padding: 15px 20px;
    margin-bottom: 20px;
    border-radius: 4px;
}
.info-card h3 {
    margin: 0 0 8px 0;
    color: #1e3a8a;
}
.info-card p {
    margin: 0;
    color: #334155;
}
</style>