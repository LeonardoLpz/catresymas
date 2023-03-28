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
      <a href="https://wa.me/525547408539" class="whatsappButton"><img src="@/assets/WhatsAppButtonGreenMedium.png" alt=""></a>      <p>Teléfono:</p>
      <a href="tel:+525547408539"> 55 4740 8539</a>
      <a href="mailto:ventas@catresymas.com">ventas@catresymas.com</a>
      <br>
      

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
  z-index: 11;
  position: relative;
}
img{
  width: 100%;
}
a{
    color: white;
    display: block;
}
.whatsappButton{
  width: 180px;
  margin: auto;
  z-index: 10;
  color:white;
  margin-top: 10px;
  margin-bottom: 5px;
}

@media (min-width: 1024px) {
  h2,p,a{
    font-size: 2vw;
  }


}
</style>
