<script setup>
import EnvioGratis from "./EnvioGratis.vue"
import ProductosItem from "./ProductosItem.vue"
</script>


<template>
  <div class="productosSection">
    <h2>PRODUCTOS</h2>
    <productos-item/>
    <envio-gratis/>
  </div>
</template>

<style scoped>
.productosSection{
  text-align: center;
  padding: 3vw;
  background-color: rgb(235, 232, 232);
  font-weight: 400;
}
img{
  margin-top: 16px;
  width: 100%;
}
h2{
  font-size: 3vw;
}
@media (min-width: 1024px) {

}
</style>
