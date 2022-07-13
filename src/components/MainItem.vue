<script setup>
import MainAsideLabel from './MainAsideLabel.vue';
import ZoomInOut from './ZoomInOut.vue';
</script>


<template>

        <main class="main">
                <MainAsideLabel></MainAsideLabel>
                <div class="main-row">
                        <ZoomInOut></ZoomInOut>
                        <div class="worldmap">World map</div>
                </div>

        </main>

</template>

<style>
.main {
        display: flex;
        flex-direction: row;
        height: 426px;
        width: 100%;
        border: 1px solid #E1E3E6;
        border-radius: 8px;
        box-shadow: 0px 4px 2px -2px rgba(27, 46, 94, 0.02);

}

.main-row {
        display: flex;
        flex-direction: column;
        align-items: flex-end;
        width: 100%;
}

.worldmap {
        max-width: 679px;
        width: 100%;
        height: 314px;
        background-color: darkslategray;
}
</style>