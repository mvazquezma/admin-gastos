<script setup>
</script>

<template>
  <div>
    <header>
      <h1>Planificador de gastos</h1>
    </header>
  </div>
</template>

<style>
  :root {
    --blue: #3b82f6;
    --white: #fff;
    --grey-light: #f5f5f5;
    --grey: #94a3b8;
    --grey-dark: #64748b;
    --black: #000;
  }
  html {
    font-size: 62.5%;
    box-sizing: border-box;
  }
  *,
  *::before,
  *::after {
    box-sizing: inherit;
  }
  body {
    font-size: 1.6rem;
    font-family: "Lato", sans-serif;
    background-color: var(--grey-light);
  }
  h1 {
    font-size: 4rem;
  }
  h2 {
    font-size: 3rem;
  }
  header {
    background-color: var(--blue);
  }
  h1 {
    padding: 3rem 0;
    margin: 0;
    color: var(--white);
    text-align: center;
  }
</style>
