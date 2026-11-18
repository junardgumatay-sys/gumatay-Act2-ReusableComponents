<template>
    <div>
        <h1>Student Directory</h1>

        <InfoCard 
            title="Semester Enrollment Notice" 
            description="Welcome to the 2026 academic year! Below is the list of active students." 
        />

        <div class="student-grid">
            <StudentCard 
                name="Junard Gumatay" 
                studentId="2026-001" 
                course="BS Inforamtion Technology" 
                yearLevel="3rd Year" 
            />

            <StudentCard 
                name="Kiesha Calderon" 
                studentId="2026-002" 
                course="BS Information Science" 
                yearLevel="2nd Year" 
            />

            <StudentCard 
                name="Paul Lagura" 
                studentId="2026-003" 
                course="BS Computer Science" 
                yearLevel="4th Year" 
            />
        </div>

        <div class="bottom-buttons">
            <AppButton label="Add New Student" color="#1e3a8a" />
            <AppButton label="Export List" color="#be3434" />
        </div>
    </div>
</template>

<style scoped>
.student-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 20px;
}
.bottom-buttons {
    margin-top: 7rem;
    display: flex;
    gap: 15px;
}
</style>