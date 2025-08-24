<script setup></script>
import Celebration from './Celebration.vue';

<template>
  <div class="app-container">
    <header class="app-header">
      <img src="/favicon.ico" alt="Logo" class="logo" />
      <h1>Bem-vindo ao Projeto Vue + Vite!</h1>
      <p class="subtitle">meu primeiro projeto </p>
    </header>
    <main class="app-main">
      <section class="card">
        <h2>Comece a desenvolver!</h2>
        <ul>
          <li>Edite <code>src/App.vue</code> para personalizar.</li>
          <li>Explore componentes Vue.</li>
          <li>Experimente instalar bibliotecas de UI.</li>
        </ul>
      </section>
  <Celebration />
    </main>
    <footer class="app-footer">
      <small>Projeto melhorado por GitHub Copilot &copy; 2025</small>
    </footer>
  </div>
</template>

<style scoped>
.app-container {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  background: linear-gradient(120deg, #f8fafc 0%, #e0e7ff 100%);
  font-family: 'Segoe UI', 'Roboto', Arial, sans-serif;
}
.app-header {
  text-align: center;
  padding: 2rem 1rem 1rem 1rem;
  background: #6366f1;
  color: #fff;
  border-bottom-left-radius: 24px;
  border-bottom-right-radius: 24px;
  box-shadow: 0 2px 8px rgba(99,102,241,0.1);
}
.logo {
  width: 64px;
  height: 64px;
  margin-bottom: 1rem;
}
.subtitle {
  font-size: 1.2rem;
  opacity: 0.85;
}
.app-main {
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}
.card {
  background: #fff;
  padding: 2rem;
  border-radius: 16px;
  box-shadow: 0 4px 24px rgba(99,102,241,0.08);
  max-width: 400px;
  width: 100%;
  text-align: left;
}
.card h2 {
  color: #6366f1;
  margin-bottom: 1rem;
}
.card ul {
  padding-left: 1.2rem;
}
.card li {
  margin-bottom: 0.5rem;
}
.app-footer {
  text-align: center;
  padding: 1rem;
  background: #e0e7ff;
  color: #6366f1;
  border-top-left-radius: 24px;
  border-top-right-radius: 24px;
  font-size: 0.95rem;
}
</style>
