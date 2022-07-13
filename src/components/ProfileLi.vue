<script setup>
import Avatar from './Avatar.vue';
import SupportBtn from './SupportBtn.vue';
import SingOut from './SingOut.vue';
</script>

<template>

    <div class="profile">
        <Avatar></Avatar>
        <div class="profile-info">
            <p class="user-name">Name Surname</p>
            <p class="user-status">Basic Membership</p>
        </div>
    </div>
    <div class="profile-btns">
        <SupportBtn v-bind:class="support - aside"></SupportBtn>
        <SingOut></SingOut>
    </div>

</template>

<style>
.profile {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding-left: 16px;
    gap: 16px;
    height: 48px;

    border-radius: 8px;
}

.profile-info {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    height: 44px;
}

.user-name {
    font-weight: 500;
    font-size: 18px;
    line-height: 24px;
    color: #5A6474;
    margin: 0;
}

.user-status {
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    color: #4E73F8;
    margin: 0;
}

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

.profile-btns {
    display: flex;
    flex-direction: column;
    padding-left: 16px;
    gap: 8px;

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
    color: #FFFFFF;
}
</style>
