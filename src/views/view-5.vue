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
          5.5
        </div>
        <div class="text-xl font-bold text-indigo-900 py-5">
          Manejo del Bus
        </div>
      </div>

      <div class="text-justify">
        <p>
          Con el objetivo de solucionar los problemas antes mencionados y de
          poder reusar nuestros diseños, así como también usar diseños
          realizados por otros grupos adoptamos el estándar de interconexión
          Wishbone.
        </p>

        <h3><b>Bus de expansión</b></h3>
        <p>
          En una primera aproximación creamos un bus de expansión
          específicamente creado para el microcontrolador. Esto tiene
          importantes desventajas, entre ellas:
        </p>
        <ul>
          <li>
            Para conectar periféricos creados por otros grupos de trabajo es
            necesario adaptarlos a la señalización del bus en cuestión
          </li>
          <li>
            Periféricos diseñados para ese bus no servían para ser usados en
            otros diseños con buses de otro tamaño. Por ejemplo: no servían para
            un bus de 16 o 32 bits sin ser adaptados.
          </li>
        </ul>
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
