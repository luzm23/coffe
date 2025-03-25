<template>
  <div class="section">
    <h2>Menú de Bebidas</h2>
    <div class="food-items">
      <div class="food-card">
        <img src="../assets/Caff.jpg" alt="Café Americano" class="food-img" />
        <div class="food-info">
          <span class="food-name">Café</span>
          <p class="description">Café negro preparado con espresso y agua caliente, ideal para los amantes del café fuerte.</p>
        </div>
      </div>
      <div class="food-card">
        <img src="../assets/Capp.jpg" alt="Capuchino" class="food-img" />
        <div class="food-info">
          <span class="food-name">Capuchino</span>
          <p class="description">Café expreso con leche vaporizada y una capa de espuma de leche, ideal para quienes disfrutan de un sabor suave.</p>
        </div>
      </div>
      <div class="food-card">
        <img src="../assets/Jugo.jpg" alt="Jugo de Naranja" class="food-img" />
        <div class="food-info">
          <span class="food-name">Jugo de Naranja</span>
          <p class="description">Jugo fresco y natural, hecho con naranjas recién exprimidas, ideal para empezar el día con energía.</p>
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
.section {
  padding: 20px;
  background-color: #f8e4b5;
  border-radius: 10px;
  margin: 15px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

h2 {
  color: #3e2723;
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
  color: #3e2723;
  margin-bottom: 10px;
}

.description {
  font-size: 1em;
  color: #7f8c8d;
  margin-bottom: 15px;
}

</style>
