<template>
  <header>
    <span>Home</span>
    <span class="separador">|</span>
    <span class="texto-caixa">Conteúdo1</span>
    <span class="separador">|</span>
    <span class="texto-caixa">Conteúdo2</span>
  </header>
  <main>Main</main>
  <footer>Rodapé</footer>
</template>

<style>
/* @import "@/assets/base.css"; */

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  font-weight: normal;
  height: 100vh;
}
header,
footer {
  height: 10%;
  background-color: black;
  color: white;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
}
header span {
  padding: 0 20px;
}

main {
  height: 80%;
}
</style>
