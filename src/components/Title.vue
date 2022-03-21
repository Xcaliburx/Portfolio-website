<template>
    <div class="text-start title">
      <nav class="d-flex flex-row justify-content-between">
        <h2>Benny K.</h2>

        <div>
          <router-link class="me-3" to="/" @click="scrollMeTo('about')">Home</router-link> |
          <a class="ms-3 me-3" href="#about">About</a> | 
          <a class="ms-3 me-3" href="#work">My Work</a>
          <a class="ms-3" href="#contact">Contact</a>
        </div>
      </nav>

      <div class="mt-5 pt-4 ms-5 ps-5">
        <h2 class="fw-bolder">Hello, I'm</h2>
        <h1>Benny Kharisma</h1>
        <h3>I make applications.</h3>
      </div>
    </div>
</template>

<style scoped>
  h1, h2, h3{
    color: white;
  }

  .title{
    background-image: url("../assets/background.webp");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 50%;
    height: 500px;
  }
</style>
