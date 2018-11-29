<template>
  <div class="thread-section">
    <Thread />
    <Thread />
  </div>
</template>

<script>
  import { Component, Vue } from 'vue-property-decorator';

  // components
  import Thread from '../Thread/index.vue';

  @Component({
    components: {
      Thread,
    }
  })
  export default class ThreadSection extends Vue {}
</script>

<style lang="scss">
  @import './ThreadSection';
</style>
