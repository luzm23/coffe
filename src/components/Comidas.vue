<template>  
  <div class="meals-section">  
    <h2>CÓMIDAS</h2>  
    <div class="meals-list">  
      <div class="meal-card">  
        <img src="../assets/enchiladas.jpg" alt="Enchiladas" class="meal-img" />  
        <span class="meal-name">Enchiladas</span>  
        <p class="meal-description">  
          Tortillas rellenas de pollo o carne, bañadas en salsa roja o verde, acompañadas de crema, queso y cebolla.  
        </p>  
      </div>  
      <div class="meal-card">  
        <img src="../assets/Filete.jpg" alt="Filete de Pollo" class="meal-img" />  
        <span class="meal-name">Filete de Pollo</span>  
        <p class="meal-description">  
          Filete de pollo a la plancha acompañado de arroz, ensalada y papas fritas.  
        </p>  
      </div>  
      <div class="meal-card">  
        <img src="../assets/Pasta.jpg" alt="Pasta Alfredo" class="meal-img" />  
        <span class="meal-name">Pasta Alfredo</span>  
        <p class="meal-description">  
          Pasta con una deliciosa salsa cremosa de queso parmesano, ajo y nata, acompañada de pechuga de pollo o camarones.  
        </p>  
      </div>  
    </div>  
  </div>  
</template>  

<script>  
export default {  
  name: 'Comidas'  
}  
</script>  

<style scoped>  
.meals-section {  
  padding: 20px;  
  background-color: #5e1f1f;  
  border-radius: 10px;  
  margin: 15px;  
}  

h2 {  
  color: #ffcccb;  
  text-align: center;  
  margin-bottom: 20px;  
  font-size: 2em;  
  text-transform: uppercase;
}  

.meals-list {  
  display: flex;  
  flex-wrap: wrap;  
  justify-content: center;  
  gap: 20px;  
}  

.meal-card {  
  background-color: white;  
  border-radius: 10px;  
  padding: 15px;  
  width: 280px;  
  text-align: center;  
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);  
  transition: transform 0.3s ease-in-out;  
}  

.meal-card:hover {  
  transform: scale(1.05);  
}  

.meal-img {  
  width: 100%;  
  height: 160px;  
  object-fit: cover;  
  border-radius: 10px;  
}  

.meal-name {  
  color: #a52a2a;  
  font-weight: bold;  
  font-size: 1.4em;  
  display: block;  
  margin-top: 10px;  
}  

.meal-description {  
  font-size: 1em;  
  color: #444;  
  margin-top: 5px;  
  line-height: 1.4;  
}  
</style>
