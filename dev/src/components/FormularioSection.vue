<script setup>
</script>

<template>
  <div class="formularioSection">
    <form action="">
      <div class="inputItem">
        <label for="Nombre">Nombre</label>
      <input type="text" name="Nombre" id="name">
      </div>
      <div class="inputItem">
        <label for="Tel">Movil</label>
      <input type="tel" name="Tel" id="tel">
      </div>
      <div class="inputItem">
        <label for="Email">Email</label>
      <input type="email" name="Email" id="email">
      </div>
      <div class="inputItem">
        <label for="Producto">Producto</label>
      <input type="text" name="Producto" id="producto">
      </div>
      <div class="inputItem">
        <label for="Piezas">Piezas</label>
      <input type="number" name="Piezas" id="piezas">
      </div>
      <div class="inputItem">
        <label for="Comentarios">Comentarios y dudas</label>
      <input type="text" name="Comentarios" id="comentarios">
      </div>
      
      <input type="submit" value="Enviar" class="button">
    </form>
    
  </div>
</template>

<style scoped>
.formularioSection{
  text-align: left;
  padding: 16px;
  background-color: var(--gris);
  color:white;
  font-weight: 400;
  color: black;
  
}
form{
  display: grid;
  grid-row-gap: 16px;
}
.inputItem{
  display: grid;
  grid-gap: 5px;
}
.inputItem input{
  border-radius: 5px;
  border:solid black 1px;
  outline: none;
  padding:3px 10px;
}
.button{
  border-radius: 5px;
  border: none;
  padding:7px;
  width: 130px;
  justify-self: center;
  background-color: var(--verde);
  color: white;
  margin-top: 10px;
}
label, input,button{
  font-size: 2vw;
}
@media (min-width: 1024px) {

}
</style>
