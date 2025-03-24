<template>
  <div class="section">
    <h2>Menú de Bebidas</h2>
    <ul>
      <li>
        <img src="../assets/CafeA.jpg" alt="Café Americano" class="food-img" />
        <span class="food-name">Café Americano</span>
        <p class="description">Café negro de espresso y agua caliente, perfecto para los aficionados al café fuerte.</p>
      </li>
      <li>
        <img src="../assets/Capuchino.jpg" alt="Capuchino" class="food-img" />
        <span class="food-name">Capuchino</span>
        <p class="description">Café expreso con leche vaporizada y espuma, perfecto para quienes prefieren un sabor suave.</p>
      </li>
      <li>
        <img src="../assets/Jugo.jpg" alt="Jugo de Naranja" class="food-img" />
        <span class="food-name">Jugo de Naranja</span>
        <p class="description">Jugo natural de naranjas recién exprimidas, perfecto para empezar el día con energía.</p>
      </li>
      <li>
        <img src="../assets/TeVerde.jpeg" alt="Té Verde" class="food-img" />
        <span class="food-name">Té Verde</span>
        <p class="description">Infusión de hojas de té verde, perfecta para relajarse y disfrutar de sus beneficios antioxidantes.</p>
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
  background-color: #B7794D;  
  border-radius: 10px;  
  margin: 10px;  
  text-align: center;  
  border: 5px solid #000;  
}  

h2 {  
  color: #130c07;  
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
  border: 2px solid #060c06;  
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
  margin: 5px 0;  /* Espacio entre el nombre y descripción */  
}  

.description {  
  font-size: 0.9em;  
  color: #251313;  
  text-align: center;  
  margin-top: 5px;  
  width: 90%;  /* Responsividad mejorada */  
}  
</style>
