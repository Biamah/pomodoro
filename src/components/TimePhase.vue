<template>
  <button class="time-phase">{{timePhase}}</button>
</template>

<script>
export default {
    name: 'TimePhase',
    props: {
        timePhase: String,
    }
}
</script>

<style>
.time-phase {
    font-size: 18px;
    font-weight: 600;
    text-transform: capitalize;
    text-align: center;
}
</style>