<template>
  <div id="app">
    <Options />

    <Pomodoro :time="time" />

    <TimePhase :timePhase="timePhase" />

    <Settings />
  </div>
</template>

<script>
import './css/global.css';

import Options from './components/Options.vue';
import Pomodoro from './components/Pomodoro.vue';
import TimePhase from './components/TimePhase.vue';
import Settings from './components/Settings.vue';

export default {
  name: 'App',
  components: {
    Options,
    Pomodoro,
    TimePhase,
    Settings
},
  data() {
    return {
      timePhase: 'start',
      time: 20
    }
  }
}
</script>

<style>
#app {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>
