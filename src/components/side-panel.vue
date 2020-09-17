<template>
    <div class="side-panel-grid">
        <h2>PORTFOLIO FILTERS</h2>
        <div>
            <h3>OIL PAINTING</h3>
            <h3>INK WASH PAINTING</h3>
            <h3>ACRYLIC PAINTING</h3>
            <h3>SPRAY PAINTING</h3>
            <h3>COLOR SKETCH POSTER</h3>
            <h3>WATER COLOR PAINTING</h3>
        </div>
        <div></div>
    </div>
</template>

<script>
    export default {
        name: "side-panel"
    }
</script>

<style scoped>
    .side-panel-grid {
        width: 100%;
        height: 100%;
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-rows: 1fr 5fr 2fr;
        background-color: darkgrey;
    }

    h3 {
        width: 90%;
        padding: 1em;
        color: white;
        font-size: 1.3rem;
        text-shadow: 1px 1px 2px black;
    }



</style>