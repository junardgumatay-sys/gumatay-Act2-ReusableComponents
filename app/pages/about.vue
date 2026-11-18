<template>
    <div>
        <h1>About This Portal</h1>

        <InfoCard 
            title="Our Mission" 
            description="This portal demonstrates how component-based architecture reduces repetitive code in NuxtJS." 
        />

        <InfoCard 
            title="How It Works" 
            description="Instead of rewriting card and button HTML on every page, we pass data dynamically using Vue Props." 
        />

        <NuxtLink to="/">
            <div class="button"><AppButton label="← Back to Student Directory" color="#475569" /></div>
        </NuxtLink>
    </div>
</template>

<style scoped>
    .button{
        margin-top: 10rem;
    }

</style>