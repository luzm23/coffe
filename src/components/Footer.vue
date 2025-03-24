<template>
    <footer class="footer">
      <div class="footer-content">
        <p>&copy; 2025 Todos los derechos reservados | Mi Cafetería</p>
        <div class="social-media">
          <a href="https://facebook.com" target="_blank" class="social-icon">Facebook</a>
          <a href="https://instagram.com" target="_blank" class="social-icon">Instagram</a>
          <a href="https://twitter.com" target="_blank" class="social-icon">Twitter</a>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer'
  }
  </script>
  
  <style scoped>
  .footer {
    background-color: #2c3e50; /* Fondo color oscuro */
    color: #fef8f8; /* Texto en blanco */
    padding: 20px;
    text-align: center;
    position: relative;
    bottom: 0;
    width: 100%;
    font-family: 'Arial', sans-serif;
  }
  
  .footer-content {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .footer-content p {
    margin: 5px 0;
    font-size: 1em;
  }
  
  .social-media {
    margin-top: 10px;
  }
  
  .social-icon {
    margin: 0 15px;
    text-decoration: none;
    color: #fef8f8;
    font-weight: bold;
  }
  
  .social-icon:hover {
    color: #ff6347; /* Rojo suave en hover */
  }
  </style>
  