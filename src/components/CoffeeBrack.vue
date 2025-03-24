<template>
    <div class="coffee-brack-container">
      <div class="text-section">
        <h2>¿Por qué "Coffee Brack"?</h2>
        <p class="description">
          El nombre "Coffee Brack" surge de la fusión de dos conceptos: el café, esa bebida que despierta todos los sentidos, y "brack", que hace referencia al momento en que una pausa se convierte en un espacio para disfrutar de una buena lectura, un café y un momento de tranquilidad. Aquí, el café se convierte en una invitación a tomar un respiro, disfrutar de la vida y explorar nuevas historias, todo acompañado de una buena taza.
        </p>
      </div>
      <div class="image-section">
        <img src="../assets/frase.jpg" alt="Café con libro" class="coffee-image" />
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CoffeeBrack'
  }
  </script>
  
  <style scoped>
  .coffee-brack-container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 40px auto;
    max-width: 1000px;
    padding: 20px;
    background: linear-gradient(135deg, #3e2723, #1e2a38);
    border-radius: 15px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.3);
  }
  
  .text-section {
    flex: 1;
    padding-right: 20px;
    color: #d7c4b7;
    font-family: 'Poppins', sans-serif;
  }
  
  h2 {
    font-size: 2em;
    color: #ffcc80;
    margin-bottom: 20px;
    font-family: 'Playfair Display', serif;
  }
  
  .description {
    font-size: 1.2em;
    line-height: 1.5;
  }
  
  .image-section {
    flex: 1;
  }
  
  .coffee-image {
  width: 80%; /* Reduce el tamaño de la imagen */
  max-width: 300px; /* Ajusta el máximo tamaño de la imagen */
  height: auto;
  border-radius: 10px;
  object-fit: cover;
}
  </style>
  