<template>
    <div class="main-content-grid">
       <div>
           <img alt="an image of oil painting" src="../assets/oilPainting.jpg">
       </div>
       <div>
           <img alt="an image of ink wash painting" src="../assets/inkWashPainting.jpg">
       </div>
       <div>
           <img alt="an image of acrylic painting" src="../assets/acrylicPainting.jpg">
       </div>
       <div>
           <img alt="an image of spray painting" src="../assets/sprayPainting.jpg">
       </div>
       <div>
           <img alt="an image of color sketch poster" src="../assets/colorSketchPoster.jpg">
       </div>
       <div>
           <img alt="an image of water color painting" src="../assets/waterColorPainting.jpg">
       </div>
    </div>
</template>

<script>
    export default {
        name: "main-content"
    }
</script>

<style scoped>
    .main-content-grid {
        width: 100%;
        height: 100%;
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: 1fr 1fr;
        row-gap: 1vh;
    }

    img {
        height: 22vw;
        width: 22vw;
        object-fit: cover;
    }


</style>