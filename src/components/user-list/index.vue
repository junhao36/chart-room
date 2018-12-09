<template>
    <div class="user-list">
        <el-menu
            default-active="2"
            class="el-menu-vertical-demo"
            background-color="#202328"
            text-color="#fff"
            active-text-color="#ffd04b">
            <el-menu-item index="2">
                <i class="el-icon-menu"></i>
                <span slot="title">导航二</span>
            </el-menu-item>
            <el-menu-item index="3">
                <i class="el-icon-document"></i>
                <span slot="title">导航三</span>
            </el-menu-item>
            <el-menu-item index="4">
                <i class="el-icon-setting"></i>
                <span slot="title">导航四</span>
            </el-menu-item>
        </el-menu>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="less" scoped>
.user-list {
    height: 100%;
    background-color: #202328;
    .el-menu {
        border-right: 0;
    }
}
</style>
