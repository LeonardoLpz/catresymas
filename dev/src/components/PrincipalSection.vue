<script setup>
</script>

<template>
  <div class="principalSection">
    <img 
      alt="logo" 
      class="logoMain" 
      src="@/assets/logoGRANDE.png"
    />
    <h2>Resistentes, prácticos y funcionales.</h2>
    <h1>soluciones rápidas para descansar bien.</h1>
    <div class="principalBanner">
      <img src="@/assets/C1.jpg" alt="catre uno" class="principalBanner-item">
      <img src="@/assets/C2.jpg" alt="catre dos" class="principalBanner-item">
      <img src="@/assets/C3.jpg" alt="catre tres" class="principalBanner-item">
    </div>
  </div>
</template>

<style scoped>
.principalSection{
  display: grid;
  padding: 16px;
}
.logoMain{
  width:300px;
  justify-self: center;
  margin-bottom: 16px;
}
h1,h2{
  font-weight: normal;
  text-align: center;
}
h2{
  font-size: 12px;
}
h1{
  font-size: 16px;
  font-style: italic;
}
.principalBanner{
  justify-self: center;
  display: flex;
  justify-content: center;
  width: calc(100vw - 32px);
  margin-top: 16px;
}
.principalBanner-item{
  width: 100px;
}
@media (min-width: 1024px) {

}
</style>
