<template>
  <div class="menu-container">
    <h2>Menú de Bebidas</h2>
    <div class="menu-grid">
      <div class="menu-item">
        <img src="../assets/macha.jpeg" alt="Té Matcha" class="food-img" />
        <div class="text-container">
          <span class="food-name">Té Matcha</span>
          <p class="description">Té verde en polvo con un sabor suave y un toque cremoso, ideal para relajarse.</p>
        </div>
      </div>
      <div class="menu-item">
        <img src="../assets/cafecaliente.jpeg" alt="Chocolate Caliente" class="food-img" />
        <div class="text-container">
          <span class="food-name">Chocolate Caliente</span>
          <p class="description">Bebida caliente y espesa hecha con chocolate derretido y leche, perfecta para días fríos.</p>
        </div>
      </div>
      <div class="menu-item">
        <img src="../assets/latte.jpeg" alt="Latte de Vainilla" class="food-img" />
        <div class="text-container">
          <span class="food-name">Latte de Vainilla</span>
          <p class="description">Café espresso con leche vaporizada y un toque de vainilla, ideal para los amantes del café dulce y suave.</p>
        </div>
      </div>
      <div class="menu-item">
        <img src="../assets/fresa.jpeg" alt="Licuado de Fresa" class="food-img" />
        <div class="text-container">
          <span class="food-name">Licuado de Fresa</span>
          <p class="description">Delicioso licuado de fresas naturales con leche, una opción dulce y cremosa.</p>
        </div>
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
.menu-container {
  padding: 30px;
  background: linear-gradient(135deg, #1e2a38, #3e2723);
  border-radius: 15px;
  margin: 40px auto;
  max-width: 100%; /* Cambio para que ocupe todo el ancho */
  box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.3);
  text-align: center;
  border: 2px solid #3e1f1b;
}

h2 {
  color: #d7c4b7;
  font-size: 2.5em;
  margin-bottom: 25px;
  font-family: 'Playfair Display', serif;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  justify-content: center;
  width: 100%; /* Asegura que ocupe todo el espacio disponible */
  max-width: 1200px; /* Puedes ajustar esto si quieres que el menú no ocupe todo el espacio en pantallas muy grandes */
  margin: 0 auto;
}

.menu-item {
  background: #3e2723;
  padding: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border-radius: 0px; /* Sin bordes redondeados */
  height: 100%; /* Asegura que cada ítem ocupe todo el espacio disponible dentro de su contenedor */
}

.menu-item:hover {
  transform: scale(1.05);
  box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.3);
}

.food-img {
  width: 180px; /* Aumentar tamaño de la imagen */
  height: 180px;
  object-fit: cover;
  border: 2px solid #3e1f1b;
}

.text-container {
  text-align: center;
  margin-top: 10px;
}

.food-name {
  color: #ffcc80;
  font-weight: bold;
  font-size: 1.5em;
  font-family: 'Playfair Display', serif;
}

.description {
  font-size: 1em;
  color: #d7c4b7;
  margin-top: 5px;
  font-family: 'Poppins', sans-serif;
}
</style>
