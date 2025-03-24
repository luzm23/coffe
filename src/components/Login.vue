<template>
  <div class="fullscreen-container">
    <div class="image-container">
      <img src="../assets/principal.jpg" alt="Vue Logo" />
      <div class="content-over-image">
        <h1 class="fancy-title">☕ Bienvenidos a <span>Coffee Brack</span> ☕</h1>
        <p class="subtitle">El mejor lugar para disfrutar de un buen café y un ambiente acogedor.</p>
        <div class="buttons-container">
          <!-- Aquí puedes agregar botones -->
        </div>
      </div>
      <div class="about-section">Sobre Nosotros</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login'
}
</script>

<style scoped>
.fullscreen-container {
  width: 100vw;
  height: 100vh;
  overflow: hidden;
}

.image-container {
  position: relative;
  width: 100%;
  height: 100%;
}

img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.content-over-image {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: white;
}

.fancy-title {
  font-size: 3.5em;
  margin-bottom: 10px;
  text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.6);
  font-family: 'Georgia', serif;
}

.fancy-title span {
  color: #ffd700;
  font-style: italic;
}

.subtitle {
  font-size: 1.2em;
  background: rgba(0, 0, 0, 0.6);
  padding: 10px 20px;
  border-radius: 10px;
  display: inline-block;
}

.buttons-container {
  display: flex;
  gap: 80px;
  justify-content: center;
}

.about-section {
  position: absolute;
  bottom: 20px;
  right: 20px;
  background: rgba(255, 255, 255, 0.8);
  padding: 10px 20px;
  border-radius: 10px;
  font-size: 1.2em;
  color: #333;
  font-weight: bold;
}
</style>