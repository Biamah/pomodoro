<template>
    <button class="option-item">{{name}}</button>
</template>

<script>
export default {
    name: 'Option',
    props: {
        name: String,
    }
}
</script>

<style>
.option-item {
    text-transform: capitalize;
    font-size: 18px;
    font-weight: 500;
}
</style>