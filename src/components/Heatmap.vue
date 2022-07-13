<script setup>
import Heatmapcomponent from './Heatmapcomponent.vue';
</script>

<template>
    <div class="heatmap">
        <div class="metricCard-header-row">
            <p class="metricCard-title">Total Revenue</p>
            <button class="dots"><img src="./dashboard_icons/free-icon-menu-483344.svg" alt="menu">
            </button>
        </div>
        <div class="revenue">
            <h1>$1,390,164.22</h1>
            <p class="label-percent">14.6% &#129125</p>
        </div>
        <div class="legend">
            <div class="legend-cmp">
                <p>$0-500</p>
                <div class="legend-icon1"></div>
            </div>
            <div class="legend-cmp">
                <p>>$500</p>
                <div class="legend-icon2"></div>
            </div>
            <div class="legend-cmp">
                <p>>$1000</p>
                <div class="legend-icon3"></div>
            </div>
        </div>
        <table class="heatmap-table">
            <tr class="heatmap-rows">
                <td class="td-title">Bundles & Deals</td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
            </tr>
            <tr>
                <td class="td-title">iOS & Android</td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
            </tr>
            <tr>
                <td class="td-title">Dataviz & Dashboards</td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
                <td>
                    <Heatmapcomponent></Heatmapcomponent>
                </td>
            </tr>
            <tr class="table-days">
                <td></td>
                <td>Mon</td>
                <td>Tue</td>
                <td>Wed</td>
                <td>Thu</td>
                <td>Fri</td>
                <td>Sat</td>
                <td>Sun</td>
            </tr>
        </table>

    </div>

</template>

<style>
.heatmap {
    border: 1px solid #E1E3E6;
    border-radius: 8px;
    max-width: 682px;
    height: 308px;

}

.dots {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #F8F8F8;
    width: 40px;
    height: 32px;
    border: none;
    border-radius: 8px;
}

.legend {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    gap: 4px;
    margin-right: 24px;
    position: relative;
    bottom: 16px;
}

.legend-icon1 {
    width: 64px;
    height: 12px;
    background: rgba(78, 115, 248, 0.24);
    border-radius: 2px;
}

.legend-icon2 {
    width: 64px;
    height: 12px;
    background: rgba(78, 115, 248, 0.4);
    border-radius: 2px;
}

.legend-icon3 {
    width: 64px;
    height: 12px;
    background: #4E73F8;
    border-radius: 2px;
}

.heatmap-table {
    padding: 0 24px 16px 24px;
    width: 100%;
    border-collapse: separate;
    border-spacing: 4px;


}

.td-title {
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    color: #757D8A;
    gap: 24px;
    padding-right: 16px;
    width: 146px;


}

.heatmap-rows {
    margin: 0;

}

.table-days {
    text-align: center;
    padding-top: 16px;
}
</style>