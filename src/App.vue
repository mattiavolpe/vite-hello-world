<script>
  export default {
    data() {
      return {
        message: "Hello world with Vite!",
      }
    }
  }
</script>

<template>
  <h1>{{ message }}</h1>
</template>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    background-color: #1e1e1e;
  }

  h1 {
    background: linear-gradient(90deg, #47c7ff, #ffb810, #8f6bfd);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
    padding: 1rem 0;
    cursor: pointer;
    transition: transform 0.6s;
  }

  h1:hover {
    transform: scale(1.3);
  }
</style>
