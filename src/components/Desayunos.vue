<template>
  <div class="meals-section">
    <h2>Menú de Desayunos</h2>
    <div class="meals-list">
      <div class="meal-card">
        <img src="../assets/Huevos.jpg" alt="Huevos Rancheros" class="meal-img" />
        <span class="meal-name">Huevos Rancheros</span>
        <p class="meal-description">
          Deliciosos huevos estrellados sobre tortillas fritas, acompañados de salsa roja o verde y frijoles.
        </p>
      </div>
      <div class="meal-card">
        <img src="../assets/descarga.jpg" alt="Chilaquiles" class="meal-img" />
        <span class="meal-name">Chilaquiles</span>
        <p class="meal-description">
          Tortillas cortadas en triángulos y bañadas en salsa verde o roja, acompañadas de pollo, crema, queso y cebolla.
        </p>
      </div>
      <div class="meal-card">
        <img src="../assets/R.jpg" alt="Hotcakes" class="meal-img" />
        <span class="meal-name">Hotcakes</span>
        <p class="meal-description">
          Esponjosos hotcakes acompañados de miel de maple, frutas frescas y mantequilla.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MenuDesayunos'
}
</script>

<style scoped>
/* Sección del menú */
.meals-section {
  padding: 20px;
  background-color: #3e6b5e; /* Color más elegante */
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
.meals-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

/* Tarjeta de comida */
.meal-card {
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
.meal-card:hover {
  transform: scale(1.05);
}

/* Imágenes dentro de las tarjetas */
.meal-img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 10px;
}

/* Nombre del platillo */
.meal-name {
  font-weight: bold;
  font-size: 1.4em;
  color: #2d2d2d;
  margin-top: 10px;
}

/* Descripción del platillo */
.meal-description {
  font-size: 1em;
  color: #444;
  line-height: 1.4;
  margin-top: 5px;
}
</style>
