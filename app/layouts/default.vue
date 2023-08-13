<template>
  <div>
    <div>
      <slot />
    </div>
    <footer>
      <p>Copyright 2023, Made by <a href="https://github.com/lebrancconvas">Poom Yimyuean (@lebrancconvas)</a></p>
    </footer>
  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>
  footer {
    position: fixed;
    height: 50px;
    width: 100%;
    text-align: center;
    left: 0;
    bottom: 0
  }
</style>
