<template>
  <div class="section">
    <h2>Pedidos</h2>
    <div class="food-items">
      <div class="food-card">
        <img src="../assets/Huevos.jpg" alt="Huevos Rancheros" class="food-img" />
        <div class="food-info">
          <span class="food-name">Huevos Rancheros</span>
          <p class="description">Deliciosos huevos estrellados sobre tortillas fritas, acompañados de salsa roja o verde, y frijoles.</p>
          <span class="quantity">Cantidad: 1</span>
        </div>
      </div>
      <div class="food-card">
        <img src="../assets/CafeA.jpg" alt="Café Americano" class="food-img" />
        <div class="food-info">
          <span class="food-name">Café Americano</span>
          <p class="description">Café negro preparado con espresso y agua caliente, ideal para los amantes del café fuerte.</p>
          <span class="quantity">Cantidad: 2</span>
        </div>
      </div>
      <div class="food-card">
        <img src="../assets/Enchiladas.jpg" alt="Enchiladas" class="food-img" />
        <div class="food-info">
          <span class="food-name">Enchiladas</span>
          <p class="description">Tortillas rellenas de pollo, bañadas en salsa roja o verde, acompañadas de crema, queso y cebolla.</p>
          <span class="quantity">Cantidad: 1</span>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Pedidos'
}
</script>

<style scoped>
.section {
  padding: 20px;
  background-color: #f4f4f9;
  border-radius: 10px;
  margin: 15px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

h2 {
  color: #2c3e50;
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
  color: #2c3e50;
  margin-bottom: 10px;
}

.description {
  font-size: 1em;
  color: #7f8c8d;
  margin-bottom: 15px;
}

.quantity {
  font-size: 1.1em;
  font-weight: bold;
  color: #e74c3c;
}
</style>
