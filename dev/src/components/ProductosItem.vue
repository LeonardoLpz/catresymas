<script setup>
</script>

<template>
  <div class="productoItemSection">
    <div class="productoItem">
      <img src="@/assets/C1.jpg" alt="Catre">
      <img src="@/assets/C4.jpg" alt="Catre">
      <div class="itemDescription">
        <p>CATRE INDIVIDUAL  N1</p>
        <p>
          Fabricado en perfil tubular y tela plástica tejida 
          sujeta por medio de 48 resortes de alambre
          galbanizado.
        </p>
        <p>Con 1.82m de largo por 65cm de ancho
          a una altura del piso al catre de 38cm</p>
        <p>Soporta hasta 100kg repartidos en su superficie.</p>
        <p class="itemPrice">PRECIO: $949</p>
      </div>
      
    </div>
    <div class="productoItem">
      <img src="@/assets/C2.jpg" alt="Catre">
      <img src="@/assets/colchoneta.jpg" alt="Catre">
      <div class="itemDescription">
        <p>COLCHONETA N1CB</p>
        <p>
          Colchoneta  en aglutinado de espuma a un espesor 
          de 3cm; con forro de tela capitonada.
        </p>
        <p class="itemPrice">PRECIO: $595</p>
      </div>
      
    </div>
  </div>
</template>

<style scoped>
.productoItem{
  display: grid;
  width: calc(100vw - 64px);
  grid-auto-flow: row;
  grid-template-columns: 1fr 1fr;
  grid-gap: 16px;
  padding: 16px;
}
img{
  margin-top: 16px;
  width: 100%;
}
.itemDescription{
  grid-column: span 2;
  text-align: left;
}
.itemPrice{
  margin-top: 16px;
  font-weight: bold;
}

@media (min-width: 1024px) {
  h2{
    font-size: 3vw;
  }
  p{
    font-size: 2vw;
    margin: auto;
  }
}
</style>
