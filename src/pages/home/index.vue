<template>
    <div class="containner">
        <ul>
            <li v-for="(item, index) in list" :key="index">
                <a :href="item.url">{{item.title}}</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    data() {
        return {
            list: [
                {
                    title: 'index',
                    url: '/pages/index/main',
                },
                {
                    title: 'todo',
                    url: '/pages/todo/main',
                },
            ],
        };
    },
};
</script>

<style lang="less">

</style>
