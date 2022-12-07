<template>
  <div class="panel">
    <h2>{{header}}</h2>
    
  </div>
</template>

<script>
export default {
  name: 'Panel',
  props: {
    record: {}
  },
  data () {
    return {
      message: 'Try change me!'
    }
  },
  methods: {
    onClick () {
      this.message = 'Here you go :)'
    }
  }
}
</script>

<style>
.card {
  padding: 20px;
  background: #FFF;
}
</style>