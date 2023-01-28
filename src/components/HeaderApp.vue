<template>
  <div id="header">
    <h1>Are you ok??</h1>
  </div>
</template>

<script>
  export default {
    name: 'HeaderApp',
  }
</script>

<style scoped>
  #header {
    width: 100%;
    height: 60px;
    padding: 12px 0 10px 0;
    background-color: #591e1c;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    position: fixed;
    top: 0;
    z-index:1000;
  }
</style>