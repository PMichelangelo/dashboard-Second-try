<template>

    <div class="zoom-container">
        <button class="zoom">-</button>
        <button class="zoom">+</button>
    </div>

</template>

<style>
.zoom-container {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    align-items: center;
    padding: 0px;
    gap: 16px;
    width: 80px;
    height: 32px;
    margin: 24px 24px 0 0;
}

.zoom {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    text-align: center;
    gap: 8px;
    width: 32px;
    height: 32px;
    background: #FFFFFF;
    border: 1px solid #E1E3E6;
    box-shadow: 0px 4px 2px -2px rgba(27, 46, 94, 0.02);
    border-radius: 8px;
    color: #757D8A;
    font-size: 16px;

}
</style>