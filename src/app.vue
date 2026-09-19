<script setup>
// Lógica de la Landing Page de AI-ToDu
</script>

<template>
  <div class="landing-page">
    <!-- Aquí irá el contenido -->
  </div>
</template>

<style scoped>
/* Diseño Responsive para Móviles */
@media (max-width: 768px) {
  .nav-container { flex-direction: column; }
  .nav-links { display: none; flex-direction: column; width: 100%; text-align: center; }
  .nav-links.active { display: flex; }
  .nav-links a { margin: 10px 0; }
  .hero-container { flex-direction: column; text-align: center; }
  .hero-img { margin-top: 30px; }
  .features-grid { grid-template-columns: 1fr; }
  .mobile-menu-btn { display: block; background: none; border: none; font-size: 24px; cursor: pointer; color: var(--primary-blue); }
}
@media (min-width: 769px) {
  .mobile-menu-btn { display: none; }
}
</style>