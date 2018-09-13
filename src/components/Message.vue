<template>
  <h1> {{ msg || 'Hello! Please click below button' }}</h1>
</template>

<script>
export default {
  name: 'message',
  props: [
    'msg'
  ]
}
</script>
