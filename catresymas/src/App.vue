<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img 
      alt="logo" 
      class="logo" 
      src="./assets/logogrande.png"
    />
  </header>
  <div class="divider">

  </div>
  <main>
      <HelloWorld msg="Leonardo!"/>
  </main>
</template>

<style scoped>
header{
  padding: 16px 16px 10px 16px;
}
.logo{
  width: 200px;
}
.divider{
  height: 17px;
  width: 100%;
  background-color: rgb(239, 127, 0);
}


@media (min-width: 1024px) {

}
</style>
