<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
import "./assets/css/common.less";
export default {
  name: "App",
  created(){

  }
};
</script>

<style>
.el-loading{
  z-index: 999999;
}
.el-loading .el-loading-spinner {
  padding: 7px;
  background: #ececec;
  width: 200px;
  color: red;
  left: 0;
  right: 0;
  margin: 0 auto;
  border-radius: 5px;
  border: 1px solid #a0a0a0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  /* margin-top: 60px; */
}
#nprogress .bar {
  background: white;
  height: 2px;
  /* filter: blur(0.5px) */
}
.ivu-form .ivu-form-item-label{
    color: #939394;
}
</style>
<style>
html,body,#app{
  height: 100%;
}
</style>
