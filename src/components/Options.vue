<template>
  <div class="options">
    <Option name="pomodoro" />
    <Option name="short break"  />
    <Option name="long break" />
  </div>
</template>

<script>
import Option from './Option.vue';

export default {
  name: 'Options',
  components: {
    Option,
  }

}
</script>

<style>
.options {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
</style>