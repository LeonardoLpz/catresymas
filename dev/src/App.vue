<script setup>
import PrincipalSection from './components/PrincipalSection.vue';
import FuncionalidadSection from './components/FuncionalidadSection.vue';
import InicioSection from './components/InicioSection.vue';
import NosotrosSection from './components/NosotrosSection.vue';
import ProductosSection from './components/ProductosSection.vue';
import PedidosSection from './components/PedidosSection.vue';
import FormularioSection from './components/FormularioSection.vue';
import ContactoSection from './components/ContactoSection.vue';
</script>

<template>
  <div>
    <header>
    <img 
      alt="logo" 
      class="logo" 
      src="@/assets/logoGRANDE.png"
    />
    </header>
    <div class="divider"></div>
    <principal-section/>
    <inicio-section/>
    <nosotros-section/>
    <funcionalidad-section/>
    <productos-section/>
    <pedidos-section v-if="false"/>
    <formulario-section v-if="false"/>
    <img src="@/assets/B-3.jpg" alt="banner" class="banner">
    <contacto-section/>
   

  </div>
</template>

<style scoped>
header{
  padding: 16px 16px 10px 16px;
}
.logo{
  width: 180px;
}
.divider{
  height: 17px;
  width: 100%;
  background-color: var(--anaranjado);
}
.banner{
  width: 100%;
}

@media (min-width: 1024px) {

}
</style>
