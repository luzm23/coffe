<template>
    <div class="section">
      <h2>Menú de Bebidas</h2>
      <ul>
        <li>
          <img src="../assets/CafeA.jpg" alt="Café Americano" class="food-img" />
          <span class="food-name">Café Americano</span>
          <p class="description">Café negro preparado con espresso y agua caliente, ideal para los amantes del café fuerte.</p>
        </li>
        <li>
          <img src="../assets/Capuchino.jpg" alt="Capuchino" class="food-img" />
          <span class="food-name">Capuchino</span>
          <p class="description">Café expreso con leche vaporizada y una capa de espuma de leche, ideal para quienes disfrutan de un sabor suave.</p>
        </li>
        <li>
          <img src="../assets/Jugo.jpg" alt="Jugo de Naranja" class="food-img" />
          <span class="food-name">Jugo de Naranja</span>
          <p class="description">Jugo fresco y natural, hecho con naranjas recién exprimidas, ideal para empezar el día con energía.</p>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Bebidas'
  }
  </script>
  
  <style scoped>
  .section {
    padding: 15px;
    background-color: #d2b48c;
    border-radius: 10px;
    margin: 10px;
  }
  
  h2 {
    color: #6b4226;
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
  </style>
  