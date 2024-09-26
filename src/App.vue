<script setup>
import Homepage from './components/Homepage.vue'
</script>

<template>
  <Homepage />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  width: 100%;
  display: inline;
  background-color: hsl(218, 28%, 13%);
  font-family: "Open Sans", system-ui;
  background-image: url('../assets/images/bg-curvy-desktop.svg');
  background-repeat: no-repeat;
  background-size: fill;
}
</style>