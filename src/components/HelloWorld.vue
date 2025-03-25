<template>
  <div>
    <!-- Llamamos al componente Login -->
    <Login />

    <Desayunos />
    <Comidas />
    <Bebidas />
    <Pedidos />
  </div>
</template>

<script>
import Login from './Login.vue';
import Desayunos from './Desayunos.vue';
import Comidas from './Comidas.vue';
import Bebidas from './Bebidas.vue';
import Pedidos from './Pedidos.vue';

export default {
  name: 'HelloWorld',
  components: {
    Login,
    Desayunos,
    Comidas,
    Bebidas,
    Pedidos
  }
}
</script>
