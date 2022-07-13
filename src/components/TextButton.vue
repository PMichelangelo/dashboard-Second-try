<template>

<div class="btn" :class="{'btn-disabled': disabled}">
    <span @click="click">
    {{title}}
    </span>
</div>
</template>

<script>
    export default {
        name: "btn",
        props:{
            title: {
                type: String,
                default: 'Press'
            },
            disabled: {
                type: Boolean,
                default: false
            }
        },
        data() {
            return{}
        },
        methods: {
            click(){
                this.$emit('click')
            }
        }
    }

</script>



<style>

.btn{
    border-radius: 4px;
    padding: 8px 16px;
    color: beige;
    background-color: red;
    cursor: pointer;
}
.btn:hover{
    background: rebeccapurple;
}

.btn-disabled{
    background-color: chartreuse;
}
</style>