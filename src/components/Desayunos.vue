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
        <img src="../assets/Tostadas-francesas.jpg" alt="Tostadas Francesas" class="food-img" />
        <span class="food-name">Tostadas Francesas</span>
        <p class="description">Rebanadas de pan empapadas en huevos y canela, servidas con jarabe de maple y frutos rojos..</p>
      </li>
      <li>
        <img src="../assets/Smoothie.jpeg" alt="Smoothie Bowl" class="food-img" />
        <span class="food-name">Smoothie Bowl</span>
        <p class="description">Base de yogurt o smoothie de frutas, adornado con granola, coco rallado y frutas frescas.</p>
      </li>
      <li>
        <img src="../assets/Omelette.webp" alt="Omelette" class="food-img" />
        <span class="food-name">Omelette</span>
        <p class="description">Huevos batidos con vegetales, queso y jamón, acompañados de pan tostado.</p>
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
  background-color: #C2A385;  
  border-radius: 10px;  
  margin: 10px;  
  text-align: center;  
  border: 5px solid #000;  

}  

h2 {  
  color: #050201;  
  text-align: center;  
}  

ul {  
  list-style: none;  
  display: flex;  
  justify-content: center;  
  align-items: flex-start;  /* Cambiado a flex-start para alinear arriba */  
  gap: 20px;  
  padding: 0;  
}  

li {  
  width: 220px;  /* Ancho consistente para todos los elementos */  
  height: 300px;  /* Alto consistente para todos los elementos */  
  padding: 10px;  
  display: flex;  
  flex-direction: column;  
  align-items: center;  
  justify-content: center;  
  border: 2px solid #070303;  
  border-radius: 5px;  
  background-color: #cec9c9;  
}  

.food-img {  
  width: 120px;  /* Ajustado para el diseño */  
  height: 100px;  
  margin-bottom: 10px;  
  border-radius: 5px;  
}  

.food-name {  
  color: black;  
  font-weight: bold;  
  font-size: 1.3em;  
  margin: 5px 0; /* Espacio entre el nombre y la descripción */  
}  

.description {  
  font-size: 0.9em;  
  color: #271313;  
  text-align: center;  
  margin-top: 5px;  
  width: 90%;  /* Opción para mantenerlo más responsivo */  
}  
</style>
