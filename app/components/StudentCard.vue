<script setup>
defineProps({
    name: String,
    course: String,
    yearLevel: String,
    studentId: String
})
</script>

<template>
    <div class="student-card">
        <div class="card-header">
            <h3>{{ name }}</h3>
        <span class="badge">{{ yearLevel }}</span>
        </div>
            <p><strong>ID:</strong> {{ studentId }}</p>
            <p><strong>Course:</strong> {{ course }}</p>
    
        <div class="card-actions">
            <AppButton label="View Profile" color="#178840" />
        </div>
    </div>
</template>

<style scoped>
.student-card {
    border: 1px solid #cbd5e1;
    border-radius: 8px;
    padding: 20px;
    background-color: white;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
}
.card-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #e2e8f0;
    padding-bottom: 10px;
    margin-bottom: 10px;
}
.card-header h3 {
    margin: 0;
}
.badge {
    background-color: #e2e8f0;
    padding: 4px 8px;
    border-radius: 12px;
    font-size: 0.8rem;
    font-weight: bold;
}
.card-actions {
    margin-top: 15px;
}
</style>