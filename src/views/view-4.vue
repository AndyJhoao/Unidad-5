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
          5.4
        </div>
        <div class="text-xl font-bold text-indigo-900 py-5">
          Estándares de Buses
        </div>
      </div>

      <div class="text-justify">
        <p>
          El bus S-100, IEEE696-1983 (retirado), fue uno de los primeros bus de
          datos diseñado en 1974como parte del Altair 8800, generalmente
          considerado el primer "ordenador personal". El bus S-100 fue el primer
          bus estándar de la industria para los fabricantes de microordenadores,
          y los ordenadores S-100, procesadores y tarjetas periféricas, fueron
          producidos por varios fabricantes.
        </p>
        <h3><b>BUS SPI</b></h3>
        <p>
          El bus de interfaz con periféricos serie (SPI) fue desarrollado
          originalmente por Motorola en los últimos años de los 80 para sus
          microcontroladores de la serie 68000. Debido a la simplicidad y al
          renombre del bus, muchos otros fabricantes han adoptado el estándar a
          lo largo de los años. Ahora se puede encontrar en una amplia variedad
          de componentes usados comúnmente en el diseño de sistemas embebidos.
          El bus SPI se utiliza sobre todo entre los microcontroladores y sus
          dispositivos periféricos inmediatos. Se encuentra comúnmente en los
          teléfonos móviles, PDAs y otros dispositivos móviles que comunican
          datos entre la CPU, el teclado, la pantalla y los chips de memoria.
          Manejo del bus
        </p>
        <h3><b>PCI</b></h3>
        <p>
          La creciente complejidad de las tarjetas y el énfasis en el bus PCI
          condujo en el año 2004 a que el uso de PC/104 con bus ISA comenzara a
          utilizarse en menor medida frente al uso del estándar PC/104 Plus.
          Para aplicaciones en las que el bus ISA es necesario, están
          disponibles las tarjetas que hacen de puente entre PCI e ISA y por
          tanto permite el uso de expansiones o tarjetas ISA en soluciones PCI-
          104. Existen numerosos desarrollos en el mercado, dentro de áreas tan
          diferentes como máquinas herramientas, control de sistemas de riego o
          aplicaciones militares. Por este motivo, el estándar PC/104 sigue
          manteniendo, gracias a su robustez, una parte alta del mercado
          embedded. <br /><br />
          Más de 100 fabricantes de tarjetas respaldan actualmente el estándar
          PC/104 y ofrecen una solución para casi cada aplicación. En
          comparación con otras soluciones, el estándar PC/104 es un estándar
          real y de ese modo permite el intercambio seguro de tarjetas de
          diferentes fabricantes, asegurando una disponibilidad a largo tiempo.
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
