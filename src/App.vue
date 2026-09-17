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
    <main>
      <section class="hero">
        <div class="container hero-container">
          <div class="hero-text">
            <h1>El sistema nervioso central de tu logística.</h1>
            <p>Centraliza tu inventario, ventas y facturación en una sola plataforma SaaS para MYPES.</p>
            <a href="#soluciones" class="btn btn-primary">Descubre Cómo</a>
          </div>
          <div class="hero-img">
            <!-- Imagen de placeholder por ahora -->
            <img src="https://placehold.co/500x300/0A2540/FFF?text=Dashboard+AI-ToDu" alt="Dashboard Preview" />
          </div>
        </div>
      </section>
    </main>

  </div>
</template>

<style scoped>
.nav-container { display: flex; justify-content: space-between; align-items: center; padding: 20px; }
.logo { font-family: 'Montserrat', sans-serif; font-size: 24px; font-weight: bold; color: var(--primary-blue); }
.nav-links a { margin: 0 15px; text-decoration: none; color: var(--text-dark); }
.hero-container { display: flex; align-items: center; gap: 20px; margin-top: 50px; }
</style>