<template>
    <div class="chart-card-w-icon">
        <div class="chart-card-label">
            <div class="chart-card-icon">
                <img src="./dashboard_icons/credit-card.svg" alt="credit_card">
            </div>
            <div class="chart-card-header-row">
                <div class="chart-column-label">
                    <h3>$16,355.49</h3>
                    <p class="chart-card-caption">Total amount</p>
                </div>
                <div class="chart-column">
                    <select name="select" id="select" class="selector">
                        <option value="value1">This week</option>
                        <option value="value2">This month</option>
                        <option value="value3">This quarter</option>
                    </select>
                    <p class="label-percent chart-percent">5% &#129125</p>
                </div>

            </div>
        </div>

        <div class="chart">
            Chart
        </div>
        <p class="comment">
            You made an extra !!component!! this week
        </p>
    </div>
</template>

<style>
.chart-card-w-icon {
    width: 328px;
    min-height: 300px;
    border: 1px solid #E1E3E6;
    border-radius: 8px;
    box-shadow: 0px 4px 8px -6px rgba(27, 46, 94, 0.03), 0px 16px 8px -4px rgba(27, 46, 94, 0.03);
}

.chart-card-label {
    display: flex;
    flex-direction: row;
    align-items: center;
    margin: 24px;

}



.chart-card-header-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    margin-left: 8px;
    align-content: center;

}

.chart-card-icon {
    display: flex;
    min-width: 40px;
    min-height: 40px;
    border-radius: 48px;
    background: rgba(78, 115, 248, 0.08);
    align-items: center;
    justify-content: center;
}

.chart-card-caption {
    font-weight: 400;
    font-size: 16px;
    line-height: 24px;
    color: #757D8A;
}

.chart-column {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 8px;
    padding-top: 2px;
}

.selector {
    height: 20px;

    border: none;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    color: #757D8A;
}

.label-percent.chart-percent {
    width: 52px;
}

.chart {
    width: 282px;
    min-height: 95px;
    margin: 34px 24px 0 24px;
    background-color: cornflowerblue;

}
</style>