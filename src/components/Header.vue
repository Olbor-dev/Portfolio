<script setup>
</script>

<template>
    <header>
        <RouterLink to="/">
        <img src="@/assets/img/Portrait-Olbor-dev.jpg" alt="Olbordev logo">
        </RouterLink>
        <nav>
            <ul>
                <RouterLink to="/">A propos</RouterLink>
                <RouterLink to="/">Projets</RouterLink>
                <RouterLink to="/">Me contacter</RouterLink>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
    header {
        font-family: 'Caveat Variable', cursive;
        position: fixed;
        background-color: white;
        width: 98%;
        top: 0;
        border-bottom: 1px solid #060640;
        background-image: url("../assets/img/HeaderFond.jpg");
        background-origin: border-box;
        background-size: 100% 200%;
    }

    ul {
        display: flex;
        justify-content: space-around;
        align-items: center;
        font-size: 1.5em;
        margin: auto;
        padding-left: 0em;
        padding-right: 0em;
    }
</style>