<template>
  <div class="body">
    <nav><Navbar /></nav>
    <main>
      <div class="main-container">
        <div class="game"> <!-- O jogo -->
          <PipeGame />
        </div>
        <section>
          <div class="section-container">
            <h1>Instruções</h1>
            <p>Insira texto aqui...
            </p>
          </div>

          <div class="section-container">
            <h1>Matéria</h1>
            <p>Insira texto aqui...
            </p>
          </div>

          <div class="section-container">
            <h1>Sobre</h1>
            <p>Este site foi criado para as avaliações das Unidades Curriculares "Estruturas Matemáticas" e "Modelos, métodos e técnicas da engenharia de software", da Universidade do Sul de Santa Catarina. <br>Projeto desenvolvido por:</p>
            <ul>
              <li><a href="https://github.com/gabriel-fresan">Gabriel Fresan</a></li>
              <li><a href="">Gabriel Caldeira</a></li>
              <li><a href="https://github.com/GabHrq">Gabriel Henrique</a></li>
              <li><a href="https://github.com/jpnunes012">João Pedro Nunes</a></li>
              <li><a href="https://github.com/RafaArauj">Rafaela Araújo</a></li>
            </ul>
          </div>
        </section>
      </div>
    </main>
    <footer>
      <p>Em construção<br>2025</p>
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

main {
  display: flex;
  justify-content: center;

  width: 100%;
}

.main-container {
  display: flex;
  flex-direction: column;
  align-items: center;

  margin: 0 1rem;
  max-width: 60rem;
  width: 100%;
  background-color: beige;
}

nav {
  background-color: aqua;
  padding: 0.4rem 0;
}

section {
  margin: 0 1rem;
  max-width: 45rem;
}

.section-container {
  background-color: azure;
  margin: 1.2rem 0;
  padding: 1.4rem;
  border-radius: 12px;
}

footer {
  background-color: grey;
  text-align: center;
}
</style>