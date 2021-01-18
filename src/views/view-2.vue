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
          5.2
        </div>
        <div class="text-xl font-bold text-indigo-900 py-5">
          Programación de puertos
        </div>
      </div>

      <div class="text-justify">
        <div class="col1">
          <p>
            Existen instrucciones en C que permiten enviar o recibir información
            por un puerto, entre ellas se tienen:
          </p>
          <ul style="list-style-type:none;">
            <li>
              OUTPUT_X (VALOR);<br />
              Saca por el puerto indicado en la “X” un valor entre 0 y 255
            </li>
            <br />
            <li>
              INPUT_X ( ); <br />
              Toma del puerto indicado en la “X” el valor que posee en sus
              terminales
            </li>
          </ul>
          <br />
          <p>
            Estas son funciones que a su vez configuran los puertos, si la
            operación es input, configura el puerto como entrada y si es output,
            configura el puerto como salida. <br /><br />
          </p>
        </div>
        <div class="col2">
          <p>
            Existen instrucciones que manejan un solo bit de un registro entre
            ellas están:
          </p>
          <ul style="list-style-type:none;">
            <li>
              OUTPUT_LOW (PIN);<br />
              Pone determinado pin a cero
            </li>
            <br />
            <li>
              OUTPUT_HIGH (PIN); <br />
              Pone determinado pin a uno
            </li>
            <br />
            <li>
              OUTPUT_BIT (PIN, VALOR); <br />
              Pone determinado pin al valor especificado
            </li>
            <br />
            <li>
              OUTPUT_TOGGLE (PIN);<br />
              Complemente el valor de determinado pin
            </li>
            <br />
            <li>
              INPUT (PIN); <br />
              Lee el valor de determinado pin
            </li>
          </ul>
          <br />
          <p>
            Estas instrucciones se comportan igual que las anteriores,
            autoconfiguran los puertos dependiendo si es una operación output
            (salida) o input (entrada). <br /><br />
            Existen instrucciones que manejan un solo bit de un registro entre
            ellas están:
          </p>
        </div>
      </div>
      <div class="col3">
        <h3>
          <b
            >CONFIGURACIÓN DE PUERTOS MEDIANTE MODIFICACIÓN DE LOS REGISTROS
            TRIS</b
          >
        </h3>
        <br />
        <p>
          Para configurar los puertos como entrada o salida, se utilizan los
          registros TRISX, donde la X representa el nombre del puerto (A, B, C,
          D, E), si se desea el puerto como entrada se debe poner a “1” y si es
          como salida se debe poner a “0” el bit correspondiente del registro
          TRIS, para ello se utilizan la funciones:
        </p>
        <br />SET_TRIS_X (VALOR);<br />
        <p>
          Se utiliza para configurar el registro tris de determinado puerto, por
          ejemplo si se pone SET_TRIS_B (0B00001111), quiere decir que se está
          configurando los cuatro bits más significativos del puerto B como
          salida y los cuatros bits menos significativos como entrada
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
