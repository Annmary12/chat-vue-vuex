<template>
  <div class="message">
    <p class="message-name">Annmary</p>
    <div class="message-content">
      Hello Douglas, how is your day going
    </div>
  </div>
</template>

<script>
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Message extends Vue {}
</script>

<style lang="scss">
  @import './Message';
</style>