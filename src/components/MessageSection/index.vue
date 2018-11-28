<template>
  <div class="message-section">
    <Message />
    <Message />
  </div>
</template>

<script>
  import { Component, Vue } from 'vue-property-decorator';

  // components
  import Message from '../Message/index.vue';

  @Component({
    components: {
      Message,
    }
  })
  export default class MessageSection extends Vue {}
</script>

<style lang="scss">
  @import './MessageSection';
</style>
