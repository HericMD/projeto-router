<template>
  <header>
    <div class="menu-esquerdo">
      <span>Home</span>
      <span class="separador">|</span>
      <span>Jogadores</span>
      <span>|</span>
      <span>Times</span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
  <main>Bem vindo</main>
  <footer>Rodapé</footer>
  <RouterView />
</template>

<style>
/* @import "@/assets/base.css"; */

body {
  background-color: #4f374d;
}

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
  background-color: #454663;
  color: #9bfae2;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  border-radius: 20px;
  padding-left: 20px;
  justify-content: space-between;
}

header span {
  padding: 0 20px;
}

main {
  height: 80%;
}
</style>
