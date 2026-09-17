<script setup>
// Lógica de la Landing Page de AI-ToDu
</script>

<template>
  <div class="landing-page">
    <header>
      <div class="container nav-container">
        <div class="logo">AI-ToDu</div>
        <nav class="nav-links">
          <a href="#beneficios">Beneficios</a>
          <a href="#soluciones">Soluciones</a>
        </nav>
        <div class="nav-actions">
          <a href="#" class="btn btn-primary">Prueba Gratis</a>
        </div>
      </div>
    </header>
  </div>
</template>

<style scoped>
.nav-container { display: flex; justify-content: space-between; align-items: center; padding: 20px; }
.logo { font-family: 'Montserrat', sans-serif; font-size: 24px; font-weight: bold; color: var(--primary-blue); }
.nav-links a { margin: 0 15px; text-decoration: none; color: var(--text-dark); }
</style>