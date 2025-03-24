<template>
  <div class="section">
    <div class="menu-header">
      <h2>🍽️ Menú de Desayunos ☕</h2>
      <p class="date">{{ currentDate }}</p>
    </div>
    <div class="menu">
      <div class="menu-item">
        <img src="../assets/Huevos.jpg" alt="Huevos Rancheros" class="food-img" />
        <div class="item-details">
          <span class="food-name">Huevos Rancheros</span>
          <p class="description">🌅 Disfruta de unos huevos estrellados sobre tortillas fritas, bañados en salsa roja o verde, acompañados de frijoles. Un clásico para empezar el día con energía.</p>
        </div>
      </div>
      <div class="menu-item">
        <img src="../assets/descarga.jpg" alt="Chilaquiles" class="food-img" />
        <div class="item-details">
          <span class="food-name">Chilaquiles</span>
          <p class="description">🥑 Crujientes tortillas bañadas en salsa verde o roja, acompañadas de pollo deshebrado, crema, queso y cebolla. Una explosión de sabor en cada bocado.</p>
        </div>
      </div>
      <div class="menu-item">
        <img src="../assets/R.jpg" alt="Hotcakes" class="food-img" />
        <div class="item-details">
          <span class="food-name">Hotcakes</span>
          <p class="description">🍿 Esponjosos hotcakes con miel de maple, frutas frescas y un toque de mantequilla derretida. Perfectos para un desayuno dulce y reconfortante.</p>
        </div>
      </div>
      <div class="menu-item">
        <img src="../assets/cuerno.jpeg" alt="Croissant con Mermelada" class="food-img" />
        <div class="item-details">
          <span class="food-name">Croissant con Mermelada</span>
          <p class="description">🥐 Crujiente por fuera, suave por dentro, servido con mermelada casera y mantequilla derretida. Ideal para un desayuno ligero y elegante.</p>
        </div>
      </div>
      <div class="menu-item">
        <img src="../assets/tostada.jpeg" alt="Tostadas Francesas" class="food-img" />
        <div class="item-details">
          <span class="food-name">Tostadas Francesas</span>
          <p class="description">🍓 Pan dorado con canela y azúcar, servido con fresas, plátano y un toque de miel. Perfecto para los amantes de los desayunos dulces.</p>
        </div>
      </div>
      <div class="menu-item">
        <img src="../assets/tazon.jpeg" alt="Avena con Almendras" class="food-img" />
        <div class="item-details">
          <span class="food-name">Avena con Almendras y Miel</span>
          <p class="description">🧀 Un tazón de avena cremosa con almendras tostadas, miel natural y un toque de canela. Nutritivo y delicioso.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Desayunos',
  data() {
    return {
      currentDate: new Date().toLocaleDateString(),
    };
  },
}
</script>

<style scoped>
.section {
  padding: 20px;
  background-color: #2c3e50;
  color: white;
  border-radius: 15px;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.5);
}

.menu-header {
  text-align: center;
  margin-bottom: 20px;
}

h2 {
  font-size: 2.2em;
  font-family: 'Georgia', serif;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
}

.date {
  font-size: 1em;
  font-family: 'Arial', sans-serif;
  color: #bdc3c7;
}

.menu {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
  padding: 10px;
}

.menu-item {
  background: #34495e;
  border-radius: 10px;
  padding: 15px;
  box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease;
}

.menu-item:hover {
  transform: scale(1.05);
}

.food-img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
  margin-bottom: 10px;
}

.item-details {
  text-align: center;
}

.food-name {
  font-size: 1.5em;
  font-weight: bold;
  color: #ecf0f1;
  margin-bottom: 5px;
}

.description {
  font-size: 1em;
  color: #bdc3c7;
  font-style: italic;
  margin-top: 5px;
}
</style>
