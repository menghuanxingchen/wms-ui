<template>
    <div class="DashBoardNeedList">
        <el-card shadow="always" style="">
            <div class="mb-xs"></div>
            <div>
                <div class="" ref="" style="height: 400px;overflow-y:auto;">
                    <ul>
                        <li>

                        </li>
                    </ul>
                </div>
            </div>
        </el-card>
    </div>
</template>

<script>
    export default {
        name: "DashBoardNeedList",
        components: {},
        props: {},
        data() {
            return {}
        },
        mounted() {
            this.reload();
        },
        methods: {
            reload() {
            },
        },
        watch: {},
        computed: {},

    }
</script>

<style lang="less" scoped>
    @import (reference) "~style/all.less";

    .DashBoardNeedList {
        .list-li{
            margin-top: 0;
            list-style-type: decimal;
            li {
                padding: 5px 0;
                .link-to {
                    padding: 0 2px;
                    color: @color--blue;
                    text-decoration: underline;
                    cursor: pointer;
                }
            }
        }
    }
</style>