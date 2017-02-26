<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="less">
@import "./assets/css/var.less";
h2{
  color: @green;
}
#app{
  height: 100%
}
</style>
