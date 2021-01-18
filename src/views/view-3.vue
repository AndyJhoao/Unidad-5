<template>
  <main
    id="data"
    class="shadow flex flex-col items-center justify-center bg-gray-200 h-full"
  >
    <div class="flex flex-col items-center justify-center py-10">
      <div class="text-6xl items-center font-black text-indigo-900">
        Unidad 5
      </div>
      <div class="text-xl font-medium text-indigo-900">
        <p>Puertos y Buses de Comunicación para Microcontroladores</p>
      </div>
    </div>
    <div class="flex h-full px-10 items-center justify-center flex-col w-3/4">
      <div class="text-left w-full">
        <div class="text-6xl font-black text-indigo-900 ">
          5.3
        </div>
        <div class="text-xl font-bold text-indigo-900 py-5">
          Aplicaciones de puertos
        </div>
      </div>

      <div class="text-justify">
        <h3><b>PUERTOS</b></h3>
        <p>
          Estas son conocidas como puertos E/S generalmente agrupados por
          puertos de 8 bits longitud.<br />
          Esto le permite leer datos del exterior o escribir en ellos desde el
          interior del microcontrolador.
        </p>

        <h3><b>CARACTERÍSTICAS</b></h3>

        <p>
          Permite manejar salidas con determinados requerimientos de corriente.
          <br />Incorporan mecanismos especiales de interrupción para el
          procesador.
        </p>

        <img class="info-image" src="img/puertos.gif" alt="Puertos" />

        <h3>
          <b>OPERACIÓN DE LECTURA EN LOS PUERTOS DEL MICROCONTROLADOR 8051</b>
        </h3>

        <p>
          La operación de lectura o de adquisición de datos no representa ningún
          tipo de problema; solamente se deberá cambiar el orden de los
          operandos en la instrucción respecto a la de escritura. Para la
          operación de lectura, el formato de la instrucción más habitual es el
          siguiente: MOV ,PX ; dato PX Los siguientes diagramas muestran cómo se
          puede introducir un dato a los puertos para que sirvan de interface.
        </p>
      </div>
      <div class="py-5">
        <router-link
          class="hover:text-yellow-700 hover:bg-gray-300 transition duration-500 rounded-md border border-gray-600 shadow-sm px-4 py-3"
          :to="{ name: 'home' }"
        >
          Regresar
        </router-link>
      </div>
    </div>
  </main>
</template>

<style scoped>
ul {
  list-style: inside !important;
}
.img {
  width: 500px;
}
</style>
