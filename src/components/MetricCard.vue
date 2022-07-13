<template>
    <div class="metricCard">
        <div class="metricCard-header-row">
            <p class="metricCard-title">Total Revenue</p>
            <select name="select" id="select" class="selector">
                <option value="value1">This week</option>
                <option value="value2">This month</option>
                <option value="value3">This quarter</option>
            </select>
        </div>
        <div class="revenue">
            <h1>$CMPNT</h1>
            <p class="label-percent">14.6% &#129125</p>
        </div>

        <p class="comment">
            You made an extra !!component!! this week
        </p>
    </div>

</template>

<style>
.metricCard {
    max-width: 330px;
    max-height: 156px;
    width: 100%;
    border: 1px solid #E1E3E6;
    border-radius: 8px;

}


.metricCard-header-row {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    margin: 24px;
    margin-bottom: 8px;
}

.metricCard-title {
    margin: 0;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    color: #757D8A;
}

.selector {
    height: 20px;

    border: none;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    color: #757D8A;
}

.revenue {
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-left: 24px;
}

p {
    margin: 0;
    padding: 0
}

.revenue-title {
    margin: 0;
    color: #404D61;
}

.comment {
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    color: #757D8A;
    margin: 16px 0 24px 24px;
}
</style>
