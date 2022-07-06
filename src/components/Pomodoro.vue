<template>
  <div class="pomodoro-circle">
    <h1 class="pomodoro-time">{{time}}</h1>
  </div>
</template>

<script>
export default {
    name: 'Pomodoro',
    props: {
      time: Number
    }
}
</script>

<style>
.pomodoro-circle {
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 100%;
  width: 200px;
  height: 200px;
  backdrop-filter: blur(20px);
  background-color: rgba(224, 215, 215, 0.30);
  position: relative;
  font-size: 30px;
  margin: 30px auto;
}
</style>