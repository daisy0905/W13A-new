<template>
    <div class="footer-grid">
        <div></div>
        <h3>RECENT POSTS</h3>
        <h3>MORE ABOUT ME</h3>
        <h3>FOLLOW ME ELSEWHERE</h3>
        <div></div>
    </div>
</template>

<script>
export default {
    name: "page-footer"
}
</script>

<style scoped>
    .footer-grid {
        width: 100%;
        min-height: 15vh;
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
        background-color: black;
    }

    h3 {
        color: white;
    }


</style>