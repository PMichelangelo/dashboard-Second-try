<script setup>
import AsideCountryLi from "./AsideCountryLi.vue";
</script>


<template>
    <aside class="aside-main">
        <h3>Most sales in Countries</h3>
        <div class="label">
            <div class="row">
                <h1 class="label-text">46,321</h1>
                <span class="label-percent"> 14.6% &#129125;</span>
            </div>
            <p class="label-sales">Sales last 90 days</p>
        </div>
        <AsideCountryLi></AsideCountryLi>

    </aside>
</template>

<style>
.aside-main {
    height: 378px;
    width: 263px;
    left: 24px;
    top: 24px;
    border-radius: 0px;
    justify-content: space-between;
    padding: 24px;
    border-right: 1px solid #E1E3E6;
}

h3 {
    margin: 0;
}

.main-aside-title {
    width: 263px;
    height: 32px;
    font-family: 'DM Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 22px;
    line-height: 32px;
    display: flex;
    align-items: center;
    color: #5A6474;
    margin: 0;
}

.label {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 4px;
    width: 263px;
    height: 68px;
    margin-top: 40px;
}

.row {
    display: flex;
    flex-direction: row;
    align-items: center;
    width: 236px;
    height: 40px;
}

.label-text {

    width: 97px;
    height: 40px;
    font-family: 'DM Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 32px;
    line-height: 40px;
    display: flex;
    align-items: center;
    color: #404D61;
}

.label-percent {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 2px 8px;
    width: 67px;
    height: 24px;
    background: rgba(7, 162, 135, 0.08);
    border-radius: 8px;
    margin-left: 8px;
    padding: 0;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    text-align: center;
    color: #07A287;
}

.label-sales {
    display: flex;
    align-items: center;
    margin: 0px;
    height: 24px;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    color: #757D8A;
}
</style>