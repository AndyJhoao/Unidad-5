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
          5.7
        </div>
        <div class="text-xl font-bold text-indigo-900 py-5">
          Comunicación
        </div>
      </div>

      <div class="text-justify">
        <p>
          Un conversor ADC puede convertir un voltaje en un número binario
          digital. Los conversores A/D son utilizados en cualquier lugar donde
          sea necesario procesar una señal, almacenarla o transportarla en forma
          digital.
        </p>
        <p>
          La resolución del conversor indica el número de valores discretos que
          se pueden obtener dependiendo del rango del voltaje de entrada.
          Usualmente es expresado en bits. Los microcontroladores típicamente
          traen incorporados conversores de 8, 10, 12 o 16 bits. Por ejemplo, un
          ADC que codifica una señal análoga de 256 valores discretos (0…255)
          tiene una resolución de 8 bits, ya que 2^8 = 256.
        </p>
        <p>
          La resolución también puede ser definida en términos eléctricos, y
          expresada en volts. La resolución de un ADC es igual al mayor voltaje
          que se pueda medir dividido por el número de valores discretos, por
          ejemplo:
        </p>
        <p>Para un rango de medida entre 0 y 10 volts</p>
        <p>
          Resolución del ADC = 12 bits: 2^12 = 4096 niveles de cuantización
          resolución del ADC en volts: (10-0)/4096 = 0.00244 volts = 2.44 mV
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
.img-2 {
  width: 700px;
}
</style>
