<template>  
  <div class="orders-section">  
    <h2>PEDIDOS</h2>  
    <div class="orders-list">  
      <div class="order-card">  
        <img src="../assets/Huevos.jpg" alt="Huevos Rancheros" class="order-img" />  
        <span class="order-name">Huevos Rancheros</span>  
        <p class="order-description">  
          Deliciosos huevos estrellados sobre tortillas fritas, acompañados de salsa roja o verde, y frijoles.  
        </p>  
      </div>  
      <div class="order-card">  
        <img src="../assets/CafeA.jpg" alt="Café Americano" class="order-img" />  
        <span class="order-name">Café Americano</span>  
        <p class="order-description">  
          Café negro preparado con espresso y agua caliente, ideal para los amantes del café fuerte.  
        </p>  
      </div>  
      <div class="order-card">  
        <img src="../assets/Enchiladas.jpg" alt="Enchiladas" class="order-img" />  
        <span class="order-name">Enchiladas</span>  
        <p class="order-description">  
          Tortillas rellenas de pollo, bañadas en salsa roja o verde, acompañadas de crema, queso y cebolla.  
        </p>   
      </div>  
    </div>  
  </div>  
</template>  

<script>  
export default {  
  name: 'Pedidos'  
}  
</script>  

<style scoped>  
/* Sección de pedidos */
.orders-section {  
  padding: 20px;  
  background-color: #5b8cb4; /* Fondo más armonioso */
  border-radius: 10px;  
  margin: 20px;  
  text-align: center;
}  

/* Estilo para el título */
h2 {  
  color: #fff;  
  margin-bottom: 30px;  
  font-size: 2em;  
  font-weight: bold;  
  text-transform: uppercase;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Sombra sutil */
}  

/* Contenedor de las tarjetas de pedido */
.orders-list {  
  display: flex;  
  flex-wrap: wrap;  
  justify-content: center;  
  gap: 20px;  
}  

/* Tarjetas de pedido */
.order-card {  
  background-color: white;  
  border-radius: 10px;  
  padding: 20px;  
  width: 300px;  
  text-align: center;  
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);  
  transition: transform 0.3s ease-in-out;  
  display: flex;  
  flex-direction: column;  
  align-items: center;  
}

/* Efecto hover en tarjetas */
.order-card:hover {  
  transform: scale(1.05);  
}  

/* Estilo de las imágenes dentro de las tarjetas */
.order-img {  
  width: 100%;  
  height: 180px;  
  object-fit: cover;  
  border-radius: 10px;  
  margin-bottom: 10px;  
}  

/* Nombre del pedido */
.order-name {  
  color: #333;  
  font-weight: bold;  
  font-size: 1.4em;  
  margin-top: 10px;  
}  

/* Descripción del pedido */
.order-description {  
  font-size: 1em;  
  color: #444;  
  line-height: 1.4;  
  margin-top: 5px;  
}  

/* Estilo para la cantidad */
.quantity {  
  font-size: 1.1em;  
  font-weight: bold;  
  margin-top: 10px;  
}  
</style>
