<script setup>
import BtnItem from './BtnItem.vue';
import NortificationBtn from './NortificationBtn.vue';
import SupportBtn from './SupportBtn.vue';
</script>

<template>

    <div class="header-text">
        <h1>Sales Analytics</h1>
        <img class="header-icon" src="/src/components/dashboard_icons/chart-increasing_1f4c8.png"
            alt="chart-increasing">
    </div>

    <input type="text" class="search" placeholder="Search">


    <div class="btn-container">
        <BtnItem v-bind:class="btn - off"></BtnItem>
        <BtnItem></BtnItem>
    </div>

    <NortificationBtn></NortificationBtn>
    <SupportBtn></SupportBtn>
</template>

<script>
</script>

<style>
.header-text {
    display: flex;
    align-items: center;
    width: 330px;
    height: 42px;
}

h1 {
    font-weight: 700;
    font-size: 32px;
    line-height: 40px;
    color: #404D61;
    margin: 0;
}

.header-icon {
    height: inherit;
    display: flex;
    align-items: center;
    position: relative;
    bottom: 8px;
    left: 5px;
}

.search {
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 12px 16px;
    gap: 8px;

    width: 448px;
    height: 48px;
    background: #FFFFFF;
    border: 1px solid #E1E3E6;
    border-radius: 8px;
}

.search-container {
    display: flex;
    flex-direction: row;
}



.btn-container {
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 4px;
    gap: 4px;
    height: 48px;
    background: #F8F8F8;
    border: 1px solid #E1E3E6;
    border-radius: 8px;

}
</style>