<template>
  <div id="app" >
    <p class="chat-header">Social Chat</p>
    <div class="app">
      <ThreadSection />
      <MessageSection />
    </div>
  </div>
</template>

<script>
import { Component, Vue } from 'vue-property-decorator';

// components
import Message from '../components/Message/index';
import MessageSection from '../components/MessageSection/index.vue';
import ThreadSection from '../components/ThreadSection/index.vue';

@Component({
  components: {
    MessageSection,
    ThreadSection
  }
})
export default class App extends Vue {}

</script>

<style lang="scss">
  @import './App';
</style>
