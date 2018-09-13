<template>
  <div id="app">
    <message-toggle />
    <list :items="['Vue js test case using Jest', 'Just message change test case']" />
  </div>
</template>

<script>
import MessageToggle from '@/components/MessageToggle.vue'
import List from '@/components/List.vue'

export default {
  components: {
    MessageToggle,
    List
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  color: #2c3e50;
  margin-top: 15%;
  margin-left: 35%;
}
</style>
