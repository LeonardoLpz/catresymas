<script setup>
</script>

<template>
  <div class="contactoSection">
    <div>
      <img src="@/assets/CONTACTO.jpg" alt="contacto">
    </div>
    <div>
      <h2>CONTACTO</h2>
      <h2>CENTRO DE DISTRIBUCION</h2>
      <br>
      <p>Horario de atención:</p>
      <p>Lunes a Viernes </p>
      <p>9:00 am a 6:00pm</p>
      <p>Sábado </p>
      <p>9:00 am a 4:00pm</p>
      <br>
      <p>Teléfono: 55 4740 8539</p>
      <p>ventas@catresymas.com</p>
    </div>
  </div>
</template>

<style scoped>
.contactoSection{
  text-align: center;
  padding: 16px;
  background-color: var(--anaranjado);
  color:white;
  font-weight: 400;
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  grid-gap: 16px;
}
img{
  width: 100%;
}
h2,p{
  font-size: 12px;
}
@media (min-width: 1024px) {

}
</style>
