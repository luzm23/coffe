<template>
  <div class="beverages-section">
    <h2>BEBIDAS</h2>
    <div class="beverage-list">
      <div class="beverage-card">
        <img src="../assets/CafeA.jpg" alt="Café Americano" class="beverage-img" />
        <span class="beverage-name">Café Americano</span>
        <p class="beverage-description">
          Café negro preparado con espresso y agua caliente, ideal para los amantes del café fuerte.
        </p>
      </div>
      <div class="beverage-card">
        <img src="../assets/Capuchino.jpg" alt="Capuchino" class="beverage-img" />
        <span class="beverage-name">Capuchino</span>
        <p class="beverage-description">
          Café expreso con leche vaporizada y una capa de espuma de leche, ideal para quienes disfrutan de un sabor suave.
        </p>
      </div>
      <div class="beverage-card">
        <img src="../assets/Jugo.jpg" alt="Jugo de Naranja" class="beverage-img" />
        <span class="beverage-name">Jugo de Naranja</span>
        <p class="beverage-description">
          Jugo fresco y natural, hecho con naranjas recién exprimidas, ideal para empezar el día con energía.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Bebidas'
}
</script>

<style scoped>
/* Sección del menú */
.beverages-section {
  padding: 20px;
  background-color: #b89f3f; /* Color más elegante */
  border-radius: 10px;
  margin: 20px;
  text-align: center;
}

/* Estilo del título */
h2 {
  color: #fff;
  margin-bottom: 20px;
  font-size: 2em;
  font-weight: bold;
  text-transform: uppercase;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

/* Contenedor de tarjetas */
.beverage-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

/* Tarjeta de bebida */
.beverage-card {
  background-color: white;
  border-radius: 10px;
  padding: 20px;
  width: 300px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease-in-out;
  display: flex;
  flex-direction: column;
  align-items: center;
}

/* Efecto hover */
.beverage-card:hover {
  transform: scale(1.05);
}

/* Imágenes dentro de las tarjetas */
.beverage-img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 10px;
}

/* Nombre de la bebida */
.beverage-name {
  font-weight: bold;
  font-size: 1.4em;
  color: #2d2d2d;
  margin-top: 10px;
}

/* Descripción de la bebida */
.beverage-description {
  font-size: 1em;
  color: #444;
  line-height: 1.4;
  margin-top: 5px;
}
</style>
