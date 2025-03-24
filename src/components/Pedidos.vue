<template>
    <div class="section">
      <h2>Pedidos</h2>
      <ul>
        <li>
          <img src="../assets/Huevos.jpg" alt="Huevos Rancheros" class="food-img" />
          <span class="food-name">Huevos Rancheros</span>
          <p class="description">Deliciosos huevos estrellados sobre tortillas fritas, acompañados de salsa roja o verde, y frijoles.</p>
          <span class="quantity">Cantidad: 1</span>
        </li>
        <li>
          <img src="../assets/CafeA.jpg" alt="Café Americano" class="food-img" />
          <span class="food-name">Café Americano</span>
          <p class="description">Café negro preparado con espresso y agua caliente, ideal para los amantes del café fuerte.</p>
          <span class="quantity">Cantidad: 2</span>
        </li>
        <li>
          <img src="../assets/Enchiladas.jpg" alt="Enchiladas" class="food-img" />
          <span class="food-name">Enchiladas</span>
          <p class="description">Tortillas rellenas de pollo, bañadas en salsa roja o verde, acompañadas de crema, queso y cebolla.</p>
          <span class="quantity">Cantidad: 1</span>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Pedidos'
  }
  </script>
  
  <style scoped>
  .section {
    padding: 15px;
    background-color: #c2f0c2;
    border-radius: 10px;
    margin: 10px;
  }
  
  h2 {
    color: #228b22;
    text-align: center;
  }
  
  ul {
    list-style: none;
    text-align: center;
  }
  
  li {
    font-size: 1.1em;
    padding: 5px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  
  .food-img {
    width: 80px;  /* Aumentando el tamaño de la imagen */
    height: 55px;
    margin-bottom: 10px;  /* Ajustando el espacio entre la imagen y el texto */
    border-radius: 5px;
  }
  
  .food-name {
    color: black;  /* Cambiando el color de las palabras a negro */
    font-weight: bold;
    font-size: 1.5em;  /* Aumentando el tamaño de la fuente */
  }
  
  .description {
    font-size: 0.9em;
    color: #666;
    margin-top: 5px;
    text-align: center;
    width: 80%;
    margin: 10px 0;
  }
  
  .quantity {
    font-size: 1.1em;
    font-weight: bold;
    margin-top: 5px;
  }
  </style>
  