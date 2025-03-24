<template>
  <div class="section">
    <h2>Pedidos</h2>
    <ul>
      <li>
        <img src="../assets/Huevos.jpg" alt="Huevos Rancheros" class="food-img" />
        <span class="food-name">Huevos Rancheros</span>
        <p class="description">Deliciosos huevos estrellados sobre tortillas fritas, acompañados de salsa roja o verde, y frijoles.</p>
      </li>
      <li>
        <img src="../assets/CafeA.jpg" alt="Café Americano" class="food-img" />
        <span class="food-name">Café Americano</span>
        <p class="description">Café negro preparado con espresso y agua caliente, ideal para los amantes del café fuerte.</p>
      </li>
      <li>
        <img src="../assets/Enchiladas.jpg" alt="Enchiladas" class="food-img" />
        <span class="food-name">Enchiladas</span>
        <p class="description">Tortillas rellenas de pollo, bañadas en salsa roja o verde, acompañadas de crema, queso y cebolla.</p>
      </li>
      <li>
        <img src="../assets/Latte.jpeg" alt="Latte" class="food-img" />
        <span class="food-name">Latte</span>
        <p class="description">Café expreso con leche vaporizada, ideal para los que buscan una bebida suave y cremosa.</p>
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
  background-color: #E5D9F4;  
  border-radius: 10px;  
  margin: 10px;  
  text-align: center;  
  border: 5px solid #000; 
  
  /* 🎨 Fondo con imagen */
  background-image: url('../assets/bebida.jpeg');  /* Ruta de tu imagen */
  background-size: cover;   /* Ajusta la imagen para cubrir todo el fondo */
  background-position: center; /* Centra la imagen */
  background-repeat: no-repeat; /* Evita que se repita */
}  

h2 {  
  color: #071307;  
  text-align: center;  
}  

ul {  
  list-style: none;  
  display: flex;  
  justify-content: center;  
  align-items: flex-start;  /* Alineación superior para uniformidad */  
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
  width: 220px;  /* Ancho constante para uniformidad */  
  height: 300px;  /* Altura constante para uniformidad */  
  border: 2px solid #110909;  
  border-radius: 5px;  
  background-color: #cec9c9;  
}  

.food-img {  
  width: 120px;  /* Ajustado para mejor proporción */  
  height: 100px;  
  margin-bottom: 10px;  
  border-radius: 5px;  
}  

.food-name {  
  color: black;  
  font-weight: bold;  
  font-size: 1.3em;  
  margin: 5px 0;  /* Espacio entre el nombre y la descripción */  
}  

.description {  
  font-size: 0.9em;  
  color: #1b0d0d;  
  text-align: center;  
  width: 90%;  /* Responsividad mejorada */  
  margin-top: 5px;  
}  

.quantity {  
  font-size: 1.1em;  
  font-weight: bold;  
  margin-top: 5px;  
}  
</style>