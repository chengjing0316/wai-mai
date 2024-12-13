<template>
  <div class="app">
    这是APP组件
    <svg class="icon" aria-hidden="true">
      <use xlink:href="#icon-hongbao"></use>
    </svg>
  </div>
</template>

<script>
  export default {
    name: "App",
  };
</script>

<style>
  .app {
    width: 160px;
    height: 160px;
    background-color: red;
  }
</style>
