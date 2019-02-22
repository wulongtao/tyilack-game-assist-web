<template>
  <div id="app">
    <el-row>
      <el-col :span="4">
        <NavMenu></NavMenu>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import NavMenu from './components/NavMenu.vue'

export default {
  name: 'app',
  components: {
      NavMenu
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
    margin: 0;
    padding: 0;
}
</style>
