<!--
 * @Author: Mr.Hope
 * @Date: 2019-06-13 21:32:08
 * @LastEditors: Mr.Hope
 * @LastEditTime: 2019-10-18 15:56:50
 * @Description: App主入口
-->
<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">主页</router-link>|
      <router-link to="/about">关于</router-link>
    </div>
    <router-view />
  </div>
</template>
<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
