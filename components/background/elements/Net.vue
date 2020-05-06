<template>
<div class="net">
  <div class="table"></div>
</div>
</template>

<script>
export default {};
</script>

<style lang='sass' scoped>
.net
  overflow: hidden

.table
  border-collapse: collapse
  position: absolute
  bottom: 0
  height: 50vh
  width: 100%
  background-size: 20px 20px
  background-image: linear-gradient(to right, $blue 1px, transparent 1px), linear-gradient(to bottom, $pink 1px, transparent 1px)
  transform: perspective(400px) rotateX(70deg) scale(2)
</style>
