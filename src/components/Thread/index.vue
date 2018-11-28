<template>
  <div class="thread">
    <div class="thread__header">
      <span class="thread__header--name">Otse</span>
      <span class="thread__header--time">11.45pm</span>
    </div>
    <span class="thread-content">
      Hi Ann!!!
    </span>
  </div>
</template>

<script>
  import { Component, Vue } from 'vue-property-decorator';

  export default class Thread extends Vue {}
</script>

<style lang="scss">
  @import './Thread';
</style>
