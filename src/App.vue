<template>
  <div id="app">
      <datepicker></datepicker>
  </div>
</template>

<script>
import Datepicker from '@/components/Datepicker'
export default {
  name: 'app',
  components: {
    Datepicker
  },
  data () {
    return {
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  height: 500px;
}

body {
    font-family: 'Helvetica Neue Light', Helvetica, sans-serif;
    background-color: #fafaff;
}
</style>
