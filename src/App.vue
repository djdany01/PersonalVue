<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style lang="less">
@import (reference) '../static/style/colors.less';

#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: @foreColor;
  word-spacing: 1px;
  letter-spacing: 1px;
}
.titleSerif{
  font-family: 'Roboto Slab', serif;
  font-size: 1.5em;
  font-weight: bold;
}
</style>
