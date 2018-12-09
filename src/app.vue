<template>
  <div id="app">
    <el-container>
        <el-aside width="240px">
          <user-list></user-list>
        </el-aside>
        <el-container>
            <container></container>
        </el-container>
    </el-container>
  </div>
</template>

<script>
import userList from './components/user-list'
import container from './components/container'
export default {
  name: 'app',
  components: {
    userList,
    container
  }
}
</script>

<style lang="less">
  #app {
    height: 100%;
    .el-container {
      height: 100%;
      .el-aside {
        height: 100%;
      } 
    }
  }
</style>
