<script setup>
import AsideLi from './AsideLi.vue'
import ProfileLi from './ProfileLi.vue';

</script>

<template>


    <aside class="aside">
        <div class="aside-title">
            <h3>Sidebar Elements</h3>
        </div>
        <hr class="aside-hr">
        <AsideLi></AsideLi>
        <ProfileLi></ProfileLi>

        <TextButton @click="click" :disabled="false"></TextButton>

    </aside>


</template>
<script>
import TextButton from './TextButton.vue';

export default {
    name: "btn",
    components: {
        TextButton
    },
    data() {
        return {

        }
    },
    methods: {
        clickBtn() {
            console.log('click')
        }
    }
}
</script>
<style>
* {
    padding: 0;
    font-family: 'DM Sans';
}



.aside {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    max-width: 330px;

    height: 640px;
    padding: 24px;
    gap: 16px;
    border: 1px solid #E1E3E6;
    border-radius: 8px;

}

h3 {
    font-weight: 700;
    font-size: 22px;
    line-height: 32px;
    color: #5A6474;
}

.aside-title {
    display: flex;
    align-items: center;

    height: 32px;
}

.aside-hr {
    display: flex;
    justify-content: flex-start;
    width: 100%;
    border-top: 1px solid #e1e3e6;
    margin: 0;
    padding: 0;
}

.aside-items {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    max-width: 282px;
    height: 328px;
    list-style: none;
}

.aside-item {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding-left: 18px;
    padding-right: 16px;
    gap: 16px;
    max-width: 282px;
    height: 48px;
    background: transparent;
    border: none;
    border-radius: 8px;
}

.li-text {
    width: 170px;
    height: 24px;
    font-weight: 400;
    font-size: 18px;
    line-height: 24px;
    display: flex;
    align-items: center;
    color: #757D8A;
    margin: 0;
}

.li-btn-list {
    border: none;
    background-color: transparent;
    display: flex;
    justify-content: flex-end;

}

a {
    text-decoration: none;
    margin: 0;
    padding: 0;
}
</style>