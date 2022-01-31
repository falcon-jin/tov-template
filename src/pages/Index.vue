<script setup lang="ts">
import { isDark, toggleDark } from "~/composables/dark";
</script>

<template>
    <div class="bg-light-100 hover:bg-dark-200">123123</div>
    <div m="6">Hello，This is the tov template！！</div>
    <div m="6" cursor="pointer" @click="toggleDark()">light: {{ isDark }} click me!!</div>
</template>