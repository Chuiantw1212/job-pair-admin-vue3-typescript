<template>
  <div class="frame">
    <RouterView />
  </div>
</template>
<script setup>
import { RouterView } from 'vue-router'
</script>
<style lang="scss">
.main {
  transition: all 0.3s;
}

@media screen and (min-width:992px) {
  .main--isNavOpen {
    padding-left: 410px;
  }
}
</style>
