<script setup>
</script>


<template>
  <div class="envioGratis">
    <h3>ENTREGA A DOMICILIO</h3>
    <h3>¡SIN COSTO EXTRA!</h3>
  </div>
</template>

<style scoped>
.envioGratis{
  max-width: 480px;
  min-width: 240px;
  width: 70%;
  padding: 16px;
  border: solid black 1px;
  margin: auto;
  border-radius: 20px;
}
h3{
  font-size: 18px;
  font-weight: normal;
}
h3:nth-of-type(2){
  font-size: 26px;
}

@media (min-width: 1024px) {
  h3{
    font-size: 2vw;
    font-weight: normal;
  }
  h3:nth-of-type(2){
    font-size: 3vw;
  }
}
</style>
