<template lang="html">
  <div class="index">
    <p @click="getUrl()" class="index-test">我是首页</p>
  </div>
</template>

<script>
export default {
  name:'index',
  methods:{
      getUrl:function(){
        this.$router.push({path:"car"})
      }
  }
}
</script>

<style lang="less">
@import "../assets/css/var.less";
.index.test{
  color:@red;
}
.index{
  width: 100%;
  height: 100%;
  background: @red;
}
</style>
