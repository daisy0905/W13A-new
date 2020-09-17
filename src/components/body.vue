<template>
    <div class="body-grid">
        <side-panel></side-panel>
        <main-content></main-content>
        <sub-content></sub-content>
    </div>
</template>

<script>
import SidePanel from "./side-panel.vue";
import CoverImage from "./cover-image.vue";
import AboutArtist from "./profile.vue"; 

export default {
    name: "page-body",
    components: {
    SidePanel,
    MainContent: CoverImage,
    SubContent: AboutArtist
  }
}
</script>

<style scoped>
    .body-grid {
        width: 100%;
        min-height: 80vh;
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1.5fr 7fr 1fr;
        column-gap: 1vw;
        row-gap: 0.5vh;
    }

</style>