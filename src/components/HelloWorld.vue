<template>
  <div>
    <!-- Llamamos al componente Login -->
    <Login />
    
    <Desayunos />
    <Bebidas />
    <CoffeeBrack /> <!-- Aquí estará el componente CoffeeBrack debajo de Bebidas -->
    <Comidas />
    <Footer /> <!-- Corregido a 'Footer' con mayúscula al inicio -->

  </div>
</template>

<script>
import Login from './Login.vue';
import Desayunos from './Desayunos.vue';
import Bebidas from './Bebidas.vue';
import CoffeeBrack from './CoffeeBrack.vue';  
import Comidas from './Comidas.vue';
import Footer from './Footer.vue';  
export default {
  name: 'HelloWorld',
  components: {
    Login,
    Desayunos,
    Bebidas,
    CoffeeBrack,
    Comidas,
    Footer  // Corregido a 'Footer' con mayúscula
  }
}
</script>
