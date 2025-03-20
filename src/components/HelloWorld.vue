<template>
  <div class="fullscreen-container">
    <div class="image-container">
      <img src="../assets/cafe.jpg" alt="Vue Logo" />
      <div class="content-over-image">
        <h1>Bienvenidos a Coffe Brack</h1>
        <div class="buttons-container">
          <button class="Cafe">Café</button>
          <button class="comida-ligera">Comida ligera</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CoffeBrack',
  // Aquí puedes agregar métodos, data, computed properties, etc.
}
</script>

<style scoped>
/* Estilos CSS específicos para este componente */
.fullscreen-container {
  width: 100vw; /* Ocupa el 100% del ancho de la pantalla */
  height: 100vh; /* Ocupa el 100% de la altura de la pantalla */
  overflow: hidden; /* Evita el desbordamiento */
}

.image-container {
  position: relative;
  width: 100%;
  height: 100%;
}

img {
  width: 100%;
  height: 100%;
  object-fit: cover; /* Asegura que la imagen cubra toda la pantalla */
}

.content-over-image {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: white; /* Color del texto para que contraste con la imagen */
}

h1 {
  font-size: 3em; /* Tamaño grande para el título */
  margin-bottom: 20px;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Sombra para mejorar la legibilidad */
}

.buttons-container {
  display: flex;
  gap: 80px; /* Espacio entre los botones */
  justify-content: center;
}

button {
  padding: 15px 30px;
  font-size: 1.2em;
  color: #fff;
  background-color: rgba(0, 123, 255, 0.8); /* Fondo semi-transparente */
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: rgba(0, 86, 179, 0.8); /* Fondo semi-transparente al hacer hover */
}

.Cafe {
  background-color: rgba(176, 144, 135, 0.8); /* Color café para el botón de Café */
}

.comida-ligera {
  background-color: rgba(176, 144, 135, 0.8); /* Color verde para el botón de Comida ligera */
}
</style>