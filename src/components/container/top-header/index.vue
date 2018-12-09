<template>
    <el-header class="tob-header">
        <el-row type="flex" justify="space-between">
            <el-col :span="7">
                <el-input placeholder="搜索历史消息" prefix-icon="el-icon-search" size="medium" v-model="keyword"></el-input>
            </el-col>
            <el-col :span="4">
                <el-dropdown>
                    <span class="el-dropdown-link">
                        下拉菜单<i class="el-icon-arrow-down el-icon--right"></i>
                    </span>
                    <el-dropdown-menu slot="dropdown">
                        <el-dropdown-item>黄金糕</el-dropdown-item>
                        <el-dropdown-item>狮子头</el-dropdown-item>
                        <el-dropdown-item>螺蛳粉</el-dropdown-item>
                    </el-dropdown-menu>
                </el-dropdown>
            </el-col>
        </el-row>
    </el-header>
</template>

<script>
export default {
  data() {
    return {
      keyword: ''
    }
  }
}
</script>

<style lang="less" scoped>
    .tob-header {
        line-height: 60px;
    } 
</style>
