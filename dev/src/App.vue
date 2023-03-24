<script setup>
import PrincipalSection from './components/PrincipalSection.vue';
import FuncionalidadSection from './components/FuncionalidadSection.vue';
import InicioSection from './components/InicioSection.vue';
import NosotrosSection from './components/NosotrosSection.vue';
import ProductosSection from './components/ProductosSection.vue';
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
  background-color: rgb(239, 127, 0);
}

@media (min-width: 1024px) {

}
</style>
