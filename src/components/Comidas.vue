<template>
  <div class="section">
    <h2>Menú de Cafetería</h2>
    <ul>
      <li>
        <img src="../assets/tacos.jpeg" alt="Tacos" class="food-img" />
        <span class="food-name">Tacos al Pastor</span>
        <p class="description">Deliciosos tacos de cerdo marinados, acompañados de piña, cebolla y cilantro fresco.</p>
      </li>
      <li>
        <img src="../assets/enchiladas.jpg" alt="Enchiladas" class="food-img" />
        <span class="food-name">Enchiladas Verdes</span>
        <p class="description">Tortillas rellenas de pollo, bañadas en salsa verde, acompañadas de crema y queso rallado.</p>
      </li>
      <li>
        <img src="../assets/pozole.jpeg" alt="Pozole" class="food-img" />
        <span class="food-name">Pozole Rojo</span>
        <p class="description">Sopa espesa de maíz hominy con carne de cerdo, aderezada con chiles secos, y acompañada de rábanos y orégano.</p>
      </li>
      <li>
        <img src="../assets/sopes.jpeg" alt="Sopes" class="food-img" />
        <span class="food-name">Sopes</span>
        <p class="description">Masa gruesa, frita, cubierta con frijoles refritos, carne desmenuzada, lechuga, crema y salsa.</p>
      </li>
      <li>
        <img src="../assets/mole.jpeg" alt="Mole Poblano" class="food-img" />
        <span class="food-name">Mole Poblano</span>
        <p class="description">Pechuga de pollo bañada con una salsa espesa de chiles, chocolate y especias, acompañada de arroz.</p>
      </li>
    </ul>
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
  background: linear-gradient(135deg, #3e2723, #1e2a38);
  border-radius: 12px;
  margin: 15px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

h2 {
  color: #fef8f8; /* Blanco suave para los textos */
  font-family: 'Arial', sans-serif;
  text-align: center;
  font-size: 2em;
  margin-bottom: 15px;
}

ul {
  list-style: none;
  padding: 0;
  display: grid;
  grid-template-columns: repeat(3, 1fr);  /* Establecer tres elementos por fila */
  gap: 15px;
}

li {
  font-size: 1.1em;
  padding: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
}

li:hover {
  transform: translateY(-5px);
}

.food-img {
  width: 120px;  /* Tamaño adecuado para la cafetería */
  height: 80px;
  object-fit: cover;
  border-radius: 6px;
  margin-bottom: 10px;
}

.food-name {
  color: #333333; /* Negro carbón */
  font-weight: bold;
  font-size: 1.4em;
  text-transform: capitalize;
  margin-bottom: 5px;
}

.description {
  font-size: 0.9em;
  color: #777; /* Gris más claro para el texto de descripción */
  text-align: center;
  width: 90%;
  margin: 0;
}
</style>
