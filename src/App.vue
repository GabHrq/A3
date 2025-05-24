<template>
  <div class="body">
    <nav><Navbar /></nav>
    <div class="container">
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
import Navbar from './components/parts/Navbar.vue'
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
  background-color: aqua;
  padding: 0.4rem 0;
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