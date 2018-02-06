<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script type="javascript">
  export default {
    name: 'app',
    data(){
      return{
        has_top: false  //  是否不需要公共头部
      }
    },
    mounted () {

    },
    watch: {
      '$route' () {

      }
    },
    methods: {

    }
  }
</script>
<style lang="less" type="text/less">
  #app{
    min-height: 100vh;
    overflow-x: hidden;

    &.no-top {
      margin-top: 0;
    }
  }
</style>
