<template>
    <div class="section">
      <h2>Menú de Desayunos</h2>
      <ul>
        <li>
          <img src="../assets/Huevos.jpg" alt="Huevos Rancheros" class="food-img" />
          <span class="food-name">Huevos Rancheros</span>
          <p class="description">Deliciosos huevos estrellados sobre tortillas fritas, acompañados de salsa roja o verde, y frijoles.</p>
        </li>
        <li>
          <img src="../assets/descarga.jpg" alt="Chilaquiles" class="food-img" />
          <span class="food-name">Chilaquiles</span>
          <p class="description">Tortillas cortadas en triángulos y bañadas en salsa verde o roja, acompañadas de pollo, crema, queso y cebolla.</p>
        </li>
        <li>
          <img src="../assets/R.jpg" alt="Hotcakes" class="food-img" />
          <span class="food-name">Hotcakes</span>
          <p class="description">Esponjosos hotcakes acompañados de miel de maple, frutas frescas y mantequilla.</p>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Desayunos'
  }
  </script>
  
  <style scoped>
  .section {
    padding: 15px;
    background-color: #f8e0c7;
    border-radius: 10px;
    margin: 10px;
  }
  
  h2 {
    color: #d2691e;
    text-align: center;
  }
  
  ul {
    list-style: none;
    text-align: center;
  }
  
  li {
    font-size: 1em;
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
  