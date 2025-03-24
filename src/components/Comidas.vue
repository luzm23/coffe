<template>
  <div class="section">
    <h2>Menú de Comidas</h2>
    <ul>
      <li>
        <img src="../assets/enchiladas.jpg" alt="Enchiladas" class="food-img" />
        <span class="food-name">Enchiladas</span>
        <p class="description">Tortillas rellenas de pollo o carne, cubiertas con salsa roja o verde, y servidas con crema, queso y cebolla.

</p>
      </li>
      <li>
        <img src="../assets/Filete.jpg" alt="Filete de Pollo" class="food-img" />
        <span class="food-name">Filete de Pollo</span>
        <p class="description">Filete de pollo a la parrilla, acompañado de arroz, ensalada fresca y papas fritas.</p>
      </li>
      <li>
        <img src="../assets/Pasta.jpg" alt="Pasta Alfredo" class="food-img" />
        <span class="food-name">Pasta Alfredo</span>
        <p class="description">Pasta con salsa cremosa de parmesano y ajo, servida con pechuga de pollo o camarones.</p>
      </li>
      <li>
        <img src="../assets/Tacos.jpeg" alt="Tacos de Carnitas" class="food-img" />
        <span class="food-name">Tacos de Carnitas</span>
        <p class="description">Tortillas de maíz rellenas de carne de cerdo desmenuzada, acompañadas de cebolla, cilantro y salsa.</p>
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
  background-color: #D26E5C;  
  border-radius: 10px;  
  margin: 10px;  
  text-align: center;  
  border: 5px solid #000;  

  /* 🎨 Fondo con imagen */
  background-image: url('../assets/Comida.jpeg');  /* Ruta de tu imagen */
  background-size: cover;   /* Ajusta la imagen para cubrir todo el fondo */
  background-position: center; /* Centra la imagen */
  background-repeat: no-repeat; /* Evita que se repita */
}  

h2 {  
  color: #08060e;  
  text-align: center;  
}  

ul {  
  list-style: none;  
  display: flex;  
  justify-content: center;  
  align-items: flex-start;  /* Alineación de los cuadros al inicio */  
  gap: 20px;  
  padding: 0;  
}  

li {  
  font-size: 1em;  
  padding: 10px;  
  display: flex;  
  flex-direction: column;  
  align-items: center;  
  justify-content: center;  
  width: 220px;  /* Ancho consistente para todos los elementos */  
  height: 300px;  /* Alto consistente para todos los elementos */  
  border: 2px solid #080606;  
  border-radius: 5px;  
  background-color: #cec9c9;  
}  

.food-img {  
  width: 120px;  /* Ajustado para un mejor layout */  
  height: 100px;  
  margin-bottom: 10px;  
  border-radius: 5px;  
}  

.food-name {  
  color: black;  
  font-weight: bold;  
  font-size: 1.3em;  
  margin: 5px 0;  /* Espaciado entre el nombre y la descripción */  
}  

.description {  
  font-size: 0.9em;  
  color: #200e0e;  
  text-align: center;  
  margin-top: 5px;  
  width: 90%; /* Ajustado para mayor responsividad */  
}  
</style>
