<template>

    <button class="sign-out">
        <img src="./dashboard_icons/free-icon-logout-992680.svg" alt="Sign out"> <span class="sign-out-text">Sing Out
        </span>
    </button>

</template>

<style>
.sign-out {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding-left: 12px;
    gap: 16px;

    height: 48px;
    border-radius: 8px;
    background-color: transparent;
    border: none;
}

.sign-out-text {
    display: flex;
    align-items: center;
    width: 170px;
    height: 24px;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    color: #757D8A;

}
</style>