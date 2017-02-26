<template lang="html">
  <div class="car">
    <p @click="goUrl()">我是购物车</p>
  </div>
</template>

<script>
export default {
  name:"car",
  methods:{
    goUrl:function(){
      this.$router.push({path:"/"})
    }
  }
}
</script>

<style lang="css">
</style>
