<template>
  <main>
    <div class="li">

      <li>naruto</li>
      <li>sasuke</li>
      <li>itachi</li>
      <li>nagato</li>
      <li>minato</li>


    </div>

    <div class="dos">
      <h1>componente2</h1>
      <p>“Muchas personas han muerto aquí, su dolor es lo que me ha ayudado a crecer.”</p>
      <img
        src="https://www.lifeder.com/wp-content/uploads/2019/01/Pain-im-625x420.jpg"
        alt="">
        <p>“La gente es estúpida, si no hago esto, no habrá paz. Luego pasará el tiempo y las heridas sanaran. Un tiempo después la gente comenzará a pelear de nuevo. Esta vez, usarán armas y conocerán de nuevo el dolor verdadero y por un corto tiempo, la paz llegará. Así nacerá un corto tiempo de paz dentro de esta cadena de odio sin final. Ese es mi deseo.”</p>

    </div>

    <div class="p">
      <p> “Somos de la misma raza, después de todo, las razones para ir a la guerra no importan. Religión, ideologías,
        recursos, tierras, rencor, amor. No importa si las razones son patéticas, son suficientes para comenzar una
        guerra. La guerra nunca acabará, razones sobran para sostener este hecho. La naturaleza humana busca el
        conflicto.”</p>
    </div>

    <Ejeuno class="eje1" />

  </main>

</template>
<script>
import Ejeuno from '@/components/Ejeuno.vue';

export default {
  components: { Ejeuno },
  name: 'InicioView',
  data() {

  }
}

</script>
<style>
.li {
  list-style: none;
  display: flex;
  justify-content: space-around;
  background-color: aquamarine;
  height: 2vh;
  border: solid 1px;
}

.dos {
  background-color: aqua;
  height: 75vh;
  border: solid 1px;

}

h1 {
  background-color: bisque;
}

.p {
  background-color: cadetblue;
  border: solid 1px;
}
</style>

