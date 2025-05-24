<template>
  <div class="body">
    <nav><Navbar /></nav>
    <div class="container">
      <header>
        <h1 class="text-2xl flex justify-center font-bold mb-4">Flappy Graphic</h1>
      </header>
      <div class="game"> <!-- O jogo -->
        <PipeGame />
      </div>
      <div class="container info">
      </div>
    </div>
    <footer class="flex">
      <p>xau</p>
    </footer>
  </div>
</template>

<script setup>
import Navbar from './components/page/Navbar.vue'
import PipeGame from './components/PipeGame.vue'
</script>

<style>
* {
  box-sizing: border-box;
}

.body {
  flex-direction: column;
  justify-content: center;
}

nav {
  position: fixed;

  margin: 0;
  width: 100%;
  background-color: aqua;
  justify-content: center;
  padding: 8px 0;
}

.nav-container {
  display: flex;
  min-width: 50%;
  width: 90%;
  justify-content: space-between;
}

.container {
  margin: 0 auto;
  flex-direction: column;
  background-color: antiquewhite;
}

footer {
  background-color: grey;
  height: 100%;
}

</style>