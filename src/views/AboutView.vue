<template>
<main>

  <h1>holii soy la vista about LI </h1>
  <eje  class="eje" />

</main>

</template>
<script >

import Eje from '@/components/Ejemplo.vue'
export default{
  components: { Eje },
  name:'AboutView',
  data(){

  }
}
</script>
<style scoped>
h1{
  background-color: chocolate;
  border: solid 1 px;
}
.eje{
border:solid red;
}



</style>