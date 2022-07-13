<template>

    <button class="btn-on">{{ title }}</button>

</template>

<script>
export default {
    name: "btn-comp",
    props: {
        title: {
            type: String,
            default: 'Give me name!'
        },
        disabled: {
            type: Boolean,
            default: false,
        }
    }
}
</script>

<style scoped >
.btn-on {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 4px 0px;
    gap: 8px;
    padding: 0;
    margin: 0;
    border: none;
    width: 159px;
    height: 40px;
    background: #FFFFFF;
    box-shadow: 0px 4px 8px -6px rgba(27, 46, 94, 0.03), 0px 16px 8px -4px rgba(27, 46, 94, 0.03);
    border-radius: 8px;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;

    color: #4E73F8;
}

.btn-off {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 4px 0px;
    gap: 8px;
    padding: 0;
    margin: 0;
    border: none;
    width: 159px;
    height: 40px;
    background: transparent;
    border-radius: 8px;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    color: #757D8A;
}
</style>