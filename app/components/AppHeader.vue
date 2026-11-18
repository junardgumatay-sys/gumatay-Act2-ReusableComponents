<template>
    <header class="header">
        <div class="logo">🎓 StudentPortal</div>
        <nav class="nav-links">
            <NuxtLink to="/">Home</NuxtLink>
            <NuxtLink to="/about">About</NuxtLink>
        </nav>
    </header>
</template>

<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    background-color: rgb(235, 113, 75);
    color: white;
}
.logo {
    font-size: 1.2rem;
    font-weight: bold;
}
.nav-links a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
}
.nav-links a:hover {
    text-decoration: underline;
}
</style>