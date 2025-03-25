<template>
  <div class="section">
    <h2>Menú de Desayunos</h2>
    <div class="food-items">
      <div class="food-card">
        <img src="../assets/Ranchero.jpg" alt="Huevos Rancheros" class="food-img" />
        <div class="food-info">
          <span class="food-name">Huevos Rancheros</span>
          <p class="description">Deliciosos huevos estrellados sobre tortillas fritas, acompañados de salsa roja o verde, y frijoles.</p>
        </div>
      </div>
      <div class="food-card">
        <img src="../assets/descarga.jpg" alt="Chilaquiles" class="food-img" />
        <div class="food-info">
          <span class="food-name">Chilaquiles</span>
          <p class="description">Tortillas cortadas en triángulos y bañadas en salsa verde o roja, acompañadas de pollo, crema, queso y cebolla.</p>
        </div>
      </div>
      <div class="food-card">
        <img src="../assets/R.jpg" alt="Hotcakes" class="food-img" />
        <div class="food-info">
          <span class="food-name">Hotcakes</span>
          <p class="description">Esponjosos hotcakes acompañados de miel de maple, frutas frescas y mantequilla.</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Desayunos'
}
</script>

<style scoped>
.section {
  padding: 20px;
  background-color: #fce8d8;
  border-radius: 10px;
  margin: 15px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

h2 {
  color: #8b4513;
  text-align: center;
  font-size: 1.8em;
  margin-bottom: 20px;
}

.food-items {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.food-card {
  background-color: #ffffff;
  padding: 20px;
  width: 250px;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease-in-out, box-shadow 0.3s ease;
}

.food-card:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.2);
}

.food-img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 15px;
}

.food-info {
  text-align: center;
}

.food-name {
  font-size: 1.3em;
  font-weight: bold;
  color: #8b4513;
  margin-bottom: 10px;
}

.description {
  font-size: 1em;
  color: #6c757d;
  margin-bottom: 15px;
}
</style>
