<template>
    <div class="section">
      <h2>Menú de Comidas</h2>
      <ul>
        <li>
          <img src="../assets/enchiladas.jpg" alt="Enchiladas" class="food-img" />
          <span class="food-name">Enchiladas</span>
          <p class="description">Tortillas rellenas de pollo o carne, bañadas en salsa roja o verde, acompañadas de crema, queso y cebolla.</p>
        </li>
        <li>
          <img src="../assets/Filete.jpg" alt="Filete de Pollo" class="food-img" />
          <span class="food-name">Filete de Pollo</span>
          <p class="description">Filete de pollo a la plancha acompañado de arroz, ensalada y papas fritas.</p>
        </li>
        <li>
          <img src="../assets/Pasta.jpg" alt="Pasta Alfredo" class="food-img" />
          <span class="food-name">Pasta Alfredo</span>
          <p class="description">Pasta con una deliciosa salsa cremosa de queso parmesano, ajo y nata, acompañada de pechuga de pollo o camarones.</p>
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
    padding: 15px;
    background-color: #f4c2c2;
    border-radius: 10px;
    margin: 10px;
  }
  
  h2 {
    color: #a52a2a;
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
    width: 80px;  
    height: 55px;
    margin-bottom: 10px;  
    border-radius: 5px;
  }
  
  .food-name {
    color: black; 
    font-weight: bold;
    font-size: 1.5em;  
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
  