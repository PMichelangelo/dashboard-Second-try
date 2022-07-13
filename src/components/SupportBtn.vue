

<template>

    <button class="support"> <img src="/src/components/dashboard_icons/messenger.svg" alt="chat"> {{ title }}
    </button>
</template>

<script>
export default {
    name: "support",
    props: {
        title: {
            type: String,
            default: "Support"
        }
    }
}
</script>






<style>
.support {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 12px 11px;
    gap: 8px;
    width: 140px;
    height: 48px;
    background: #4E73F8;
    border-radius: 8px;
    border: none;
    font-weight: 500;
    font-size: 18px;
    line-height: 24px;
    color: #FFFFFF;
}

.support-aside {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 12px 11px;
    gap: 8px;
    width: 140px;
    height: 48px;
    background: #4E73F8;
    border-radius: 8px;
    border: none;
    font-weight: 500;
    font-size: 18px;
    line-height: 24px;
    color: black;
}
</style>