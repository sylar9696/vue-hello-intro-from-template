<template>

  <NavBar/>

  <h1 class="text-danger text-uppercase">Ciao Mondo</h1>

  <hr>

  <CompSaluto/>

  <hr>

  <CompTitoloColore/>

</template>


<script>
import CompSaluto from './components/CompSaluto.vue'
import CompTitoloColore from './components/CompTitoloColore.vue'
import NavBar from './components/header/NavBar.vue'


  export default{
    components: {
      CompSaluto,
      CompTitoloColore,
      NavBar
    }
  }
</script>


<style>
  h1{
    color: red;
  }
</style>
