<template>

<div class="container-column">
    <ul class="countries">
        <li class="countries-name"> <div class="circle green"></div>Australia</li>
        <li class="countries-name"><div class="circle blue"></div>Canada</li>
        <li class="countries-name"><div class="circle orange"></div>Brazil</li>
        <li class="countries-name"><div class="circle red"></div>Greenland</li>
        <li class="countries-name"><div class="circle grey"></div>Other countries</li>
    </ul>
    <ul class="percentage-sales">
        <li class="countries-percentage">17,159</li>
        <li class="countries-percentage">15,854</li>
        <li class="countries-percentage">9,573</li>
        <li class="countries-percentage">2,362</li>
        <li class="countries-percentage">&lsaquo;1000</li>
    </ul>
</div>

</template>

<style>
.container-column{
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;
gap: 24px;

width: 263px;
height: 198px;
margin-top: 40px;
color: #5A6474;
}

.countries{
display: flex;
flex-direction: column;
justify-content: space-between;
align-items: flex-start;
padding: 0px;
gap: 16px;
width: 152px;
height: 198px;
margin: 0;
}

.countries-name{
width: 152px;;
height: 24px;
font-weight: 400;
font-size: 18px;
line-height: 24px;
display: flex;
align-items: center;
color: #5A6474;
}

.percentage-sales{
display: flex;
flex-direction: column;
justify-content: space-between;
align-items: flex-end;
padding: 0px;
gap: 16px;
margin: 0;
width: 87px;
height: 198px;
list-style: none;
}

.circle{
    width: 12px;
    height: 12px;
    border-radius: 100%;
    margin-right: 8px;
}

.circle.green{
    background-color: #07A287;
}

.circle.blue{
    background-color:#4E73F8;
}

.circle.orange{
    background-color:#FCA549;
}

.circle.red{
    background-color: #F43C3C;
}

.circle.grey{
    background-color:#E1E3E6;
}
</style>