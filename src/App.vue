<template>
  <div id="app">
    <pomodoro-list></pomodoro-list>
  </div>
</template>

<script>
import PomodoroList from './components/PomodoroList'

export default {
  name: 'App',
  components: {
    PomodoroList
  }
}
</script>

<style lang="scss">
@import '~bootstrap';
@import '~bootstrap-vue';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
