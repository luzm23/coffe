<template>
    <div class="fullscreen-container">
      <div class="image-container">
        <img src="../assets/fon.jpg" alt="Vue Logo" />
        <div class="content-over-image">
          <div class="buttons-container">
           
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Login'
  }
  </script>
  
  <style scoped>
  .fullscreen-container {
    width: 88vw;
    height: 40vh;
    overflow: hidden;
  }
  
  .image-container {
    position: relative;
    width: 95%;
    height: 90%;
  }
  
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
  .content-over-image {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    color: white;
  }
  
  h1 {
    font-size: 3em;
    margin-bottom: 20px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
  }
  
  .buttons-container {
    display: flex;
    gap: 80px;
    justify-content: center;
  }
  
  button {
    padding: 15px 30px;
    font-size: 1.2em;
    color: #fff;
    background-color: rgba(0, 123, 255, 0.8);
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: transform 0.3s ease, background-color 0.3s ease;
  }
  
  button:hover {
    transform: scale(1.1);
    background-color: rgba(0, 86, 179, 0.8);
  }
  
  .Cafe {
    background-color: rgba(176, 144, 135, 0.8);
  }
  
  .comida-ligera {
    background-color: rgba(176, 144, 135, 0.8);
  }
  </style>
  