<template>
    <div class="g-page">
        <div class="page__bd page__bd_spacing">
            <ul>
                <li v-for="(item, index) in list" :key="index">
                    <a :href="item.url">{{item.title}}</a>
                </li>
            </ul>
            <table>
                <thead>
                    <th></th>
                    <th>Monday</th>
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thurday</th>
                    <th>Friday</th>
                    <th>Saturday</th>
                    <th>Sunday</th>
                </thead>
            </table>
        </div>
    </div>
</template>

<script>
// import VTable from 'vue-easytable';

// require('vue-easytable/libs/themes-base/index.css');

export default {
    components: {
        // VTable,
    },
    data() {
        return {
            list: [
                {
                    title: 'index',
                    url: '/pages/index/main',
                },
                {
                    title: 'logs',
                    url: '/pages/logs/main',
                },
                {
                    title: 'todo',
                    url: '/pages/todo/main',
                },
            ],
            columns: [

            ],
        };
    },
};
</script>

<style lang="less">

</style>
