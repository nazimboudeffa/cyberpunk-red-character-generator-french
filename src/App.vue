<template>
  <div id="app">
    <header class="header">
      <div class="container">
      <router-link to="/" class="header__link">Cyberpunk Red Générateur de Personnage</router-link>
      </div>
    </header>

    <main class="container">
      <router-view />
    </main>

    <footer class="footer container">
      <div class="footer__content">
        <p>
          Contenu &copy; R. Talsorian Games, Inc.<br />
          Code &copy; Ben Serrette<br />
          Traduction en Français Nazim Boudeffa
        </p>
      </div>
      <div class="footer__content">
        <a href="https://github.com/nazimboudeffa/cyberpunk-red-character-generator-french">Contribuer sur Github</a>
      </div>
    </footer>
  </div>
</template>
