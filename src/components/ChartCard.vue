<template>
    <div class="chart-card">
        <div class="wavy-curve">

        </div>
        <div class="label chart-mini">
            <div class="row chart-row">
                <h3>46,321</h3>
                <span class="label-percent"><img src="./dashboard_icons/arrow-up.svg" alt="arrow_up"> +15%</span>
            </div>
            <p class="label-sales"> Total amount</p>
        </div>
    </div>

</template>

<style>
.wavy-curve {
    width: 282px;
    height: 62px;
    background-color: #4E73F8;
    margin: 24px 24px 0 24px;
}

.chart-column-label.mini {
    margin-left: 24px;
}

.chart-card {
    width: 328px;
    height: 162px;
    border: 1px solid #E1E3E6;
    border-radius: 8px;
}

.chart-mini {
    margin-left: 24px;
    margin-top: 0;
    gap: 0;
    max-height: 56px;
}

.chart-row {
    height: 32px;
}
</style>