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

      <section id="beneficios" class="features container">
        <h2>Innovación Adaptable para tu Negocio</h2>
        <div class="features-grid">
          <div class="feature-card">
            <h3>📦 Unificación</h3>
            <p>Conecta en tiempo real tus flujos de inventario.</p>
          </div>
          <div class="feature-card">
            <h3>📈 Balance Inteligente</h3>
            <p>Descubre tu margen de ganancia real.</p>
          </div>
          <div class="feature-card">
            <h3>🔔 Alertas</h3>
            <p>Notificaciones de stock mínimo.</p>
          </div>
        </div>
      </section>

      <section id="soluciones" class="segments container">
        <h2>Hecho para quienes mueven la economía</h2>
        <div class="segments-grid">
          <div class="segment-card">
            <h3>Para Dueños y Gerentes</h3>
            <p>Dashboard directivo accesible desde tu celular.</p>
          </div>
          <div class="segment-card">
            <h3>Para Operarios de Almacén</h3>
            <p>Interfaces rápidas y búsqueda ágil de productos.</p>

          </div>
        </div>
      </section>

      <section class="cta-section">
        <div class="container">
          <h2>¿Listo para modernizar tu cadena de suministro?</h2>
          <a href="#" class="btn btn-primary">Crea tu cuenta ahora</a>
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
.features-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px; margin-top: 30px; }
.feature-card { background: white; padding: 20px; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
</style>

