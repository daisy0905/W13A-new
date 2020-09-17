<template>
    <div class="header-grid">
        <img alt="Artist logo" src="../assets/logo.jpg">
        <div></div>
        <h3>ABOUT</h3>
        <h3>PORTFOLIO</h3>
        <h3>EXHIBITION</h3>
        <h3>BLOG</h3>
        <h3>CONTACT</h3>
    </div>
</template>

<script>
    export default {
        name: "page-header"
    }
</script>

<style scoped>
    .header-grid {
        width: 100%;
        height: 15vh;
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 2fr 1fr 1fr 1fr 1fr 1fr;
    }

    img {
        height: 80%;
        object-fit: cover;
    }


</style>