<template>
  <div class="section">
    <h2>Menú de Comidas</h2>
    <div class="food-items">
      <div class="food-card">
        <img src="../assets/enchiladas.jpg" alt="Enchiladas" class="food-img" />
        <div class="food-info">
          <span class="food-name">Enchiladas</span>
          <p class="description">Tortillas rellenas de pollo o carne, bañadas en salsa roja o verde, acompañadas de crema, queso y cebolla.</p>
        </div>
      </div>
      <div class="food-card">
        <img src="../assets/Filete.jpg" alt="Filete de Pollo" class="food-img" />
        <div class="food-info">
          <span class="food-name">Filete de Pollo</span>
          <p class="description">Filete de pollo a la plancha acompañado de arroz, ensalada y papas fritas.</p>
        </div>
      </div>
      <div class="food-card">
        <img src="../assets/Pasta.jpg" alt="Pasta Alfredo" class="food-img" />
        <div class="food-info">
          <span class="food-name">Pasta Alfredo</span>
          <p class="description">Pasta con una deliciosa salsa cremosa de queso parmesano, ajo y nata, acompañada de pechuga de pollo o camarones.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Comidas'
}
</script>

<style scoped>
.section {
  padding: 20px;
  background-color: #f8d7da;
  border-radius: 10px;
  margin: 15px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

h2 {
  color: #721c24;
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
  color: #721c24;
  margin-bottom: 10px;
}

.description {
  font-size: 1em;
  color: #6c757d;
  margin-bottom: 15px;
}
</style>
