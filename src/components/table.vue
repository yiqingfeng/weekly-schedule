<template>
    <div class="m-table">
        <div class="table_hd">
        </div>
        <div class="table_bd">
        </div>
    </div>
</template>

<script>
export default {
    props: {
        columns: {
            type: Array,
            isRequired: true,
        },
        data: Array,
        emptyTip: String,
    },
    mounted() {
        console.log('object');
    },
    methods: {

    },
};
</script>

<style lang="less">
.m-table {

}
</style>
