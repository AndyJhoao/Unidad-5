<template>
  <main
    id="data"
    class="shadow flex flex-col items-center justify-center bg-gray-200 h-full py-2"
  >
    <!-- <div class="fondo"></div> -->
    <div class="flex flex-col items-center justify-center py-10">
      <div class="sm:text-6xl items-center font-black text-indigo-900 text-5xl">
        Unidad 5
      </div>
      <div class="text-xl font-medium text-indigo-900">
        <p>Puertos y Buses de Comunicación para Microcontroladores</p>
      </div>
    </div>
    <div class="flex h-full">
      <div class="flex flex-col h-full content-start">
        <div
          class="xl:flex md:flex md:flex-row items-center align-center justify-center flex-col"
        >
          <div
            class="xl:w-1/4 md:w-2/4 w-screen xl:px-0 md:px-10 px-16 xl:mx-20 md:mx-0 mx-0 "
          >
            <div class="sm:text-6xl font-black text-indigo-900 text-5xl">
              5.1
            </div>
            <div class="text-xl font-bold text-indigo-900 py-5 title-header">
              Tipos de Puertos
            </div>
            <div class="text-justify parrafo">
              Cualquier aplicación de un sistema digital basado en un
              microprocesador o microcontrolador requiere la transferencia de
              datos entre circuitos externos al microprocesador y él mismo.
              Estas transferencias constituyen las operaciones llamadas ENTRADA
              y SALIDA, (I/O).
            </div>
            <img
              class="fondo-2"
              src="https://www.areatecnologia.com/informatica/imagenes/puertos-usb.jpg"
              alt="wan"
            />
            <div class="py-5 text-center">
              <router-link
                class="hover:text-yellow-700 hover:bg-gray-300 transition duration-500 rounded-md border border-gray-600 shadow-sm px-4 py-3"
                :to="{ name: 'view-1' }"
              >
                Leer más...
              </router-link>
            </div>
            <hr class="my-10" />
          </div>
          <div
            class="xl:w-1/4 md:w-2/4 w-screen xl:px-0 md:px-10 px-16 xl:mx-20 md:mx-0 mx-0"
          >
            <div class="sm:text-6xl font-black text-indigo-900 text-5xl">
              5.2
            </div>
            <div class="text-xl font-bold text-indigo-900 py-5 title-header">
              Programación de puertos
            </div>
            <div class="text-justify parrafo">
              Existen instrucciones que manejan un solo bit de un registro entre
              ellas están: OUTPUT_LOW (PIN); Pone determinado pin a cero
            </div>
            <img
              class="fondo-2"
              src="https://3.bp.blogspot.com/-Nfc-5beSzy0/VJBelMO4RQI/AAAAAAAAABk/zStgtm3I1zw/s1600/image004.gif"
              alt="wan"
            />
            <div class="py-5 text-center">
              <router-link
                class="hover:text-yellow-700 hover:bg-gray-300 transition duration-500 rounded-md border border-gray-600 shadow-sm px-4 py-3"
                :to="{ name: 'view-2' }"
              >
                Leer más...
              </router-link>
            </div>
            <hr class="my-10" />
          </div>
        </div>
        <div
          class="xl:flex md:flex md:flex-row items-center justify-center flex-col"
        >
          <div
            class="xl:w-1/4 md:w-2/4 w-screen xl:px-0 md:px-10 px-16 xl:mx-20 md:mx-0 mx-0"
          >
            <div class="sm:text-6xl font-black text-indigo-900 text-5xl">
              5.3
            </div>
            <div class="text-xl font-bold text-indigo-900 py-5 title-header">
              Aplicaciones de puertos
            </div>
            <div class="text-justify parrafo">
              Estas son conocidas como puertos E/S generalmente agrupados por
              puertos de 8 bits longitud. Esto le permite leer datos del
              exterior o escribir en ellos desde el interior del
              microcontrolador.
            </div>
            <img
              class="fondo-2"
              src="https://0901.static.prezi.com/preview/v2/djzfbgsdskk2jq7zxuskzlhsjx6jc3sachvcdoaizecfr3dnitcq_3_0.png"
              alt="wan"
            />
            <div class="py-5 text-center">
              <router-link
                class="hover:text-yellow-700 hover:bg-gray-300 transition duration-500 rounded-md border border-gray-600 shadow-sm px-4 py-3"
                :to="{ name: 'view-3' }"
              >
                Leer más...
              </router-link>
            </div>
            <hr class="my-10" />
          </div>
          <div
            class="xl:w-1/4 md:w-2/4 w-screen xl:px-0 md:px-10 px-16 xl:mx-20 md:mx-0 mx-0"
          >
            <div class="sm:text-6xl font-black text-indigo-900 text-5xl">
              5.4
            </div>
            <div class="text-xl font-bold text-indigo-900 py-5 title-header">
              Estándares de Buses
            </div>
            <div class="text-justify parrafo">
              El bus S-100, IEEE696-1983 (retirado), fue uno de los primeros bus
              de datos diseñado en 1974como parte del Altair 8800, generalmente
              considerado el primer "ordenador personal". El bus S-100 fue el
              primer bus estándar de la industria para los fabricantes de
              microordenadores, y los ordenadores S-100, procesadores y tarjetas
              periféricas, fueron producidos por varios fabricantes.
            </div>
            <img
              class="fondo-2"
              src="https://image.slidesharecdn.com/comunicacioninternadelacomputadora-110222061041-phpapp02/95/buses-direccionamiento-temporizacion-5-728.jpg?cb=1349750208"
              alt="wan"
            />
            <div class="py-5 text-center">
              <router-link
                class="hover:text-yellow-700 hover:bg-gray-300 transition duration-500 rounded-md border border-gray-600 shadow-sm px-4 py-3"
                :to="{ name: 'view-4' }"
              >
                Leer más...
              </router-link>
            </div>
            <hr class="my-10" />
          </div>
        </div>
        <div
          class="xl:flex md:flex md:flex-row items-center justify-center flex-col"
        >
          <div
            class="xl:w-1/4 md:w-2/4 w-screen xl:px-0 md:px-10 px-16 xl:mx-20 md:mx-0 mx-0"
          >
            <div class="sm:text-6xl font-black text-indigo-900 text-5xl">
              5.5
            </div>
            <div class="text-xl font-bold text-indigo-900 py-5 title-header">
              Manejo del Bus
            </div>
            <div class="text-justify parrafo">
              Con el objetivo de solucionar los problemas antes mencionados y de
              poder reusar nuestros diseños, así como también usar diseños
              realizados por otros grupos adoptamos el estándar de interconexión
              Wishbone.
            </div>
            <img
              class="fondo-2"
              src="https://lh3.googleusercontent.com/proxy/AbGZtS6rq5u0DUYAv1JILgJHctVpTrtsEZr97gs1x76-yVPHTX3n8i2WmuYVWL3jKu98tJzkepu9EbIGaYpp6gmkRK90lDu-y1x2QVJZ"
              alt="wan"
            />
            <div class="py-5 text-center">
              <router-link
                class="hover:text-yellow-700 hover:bg-gray-300 transition duration-500 rounded-md border border-gray-600 shadow-sm px-4 py-3"
                :to="{ name: 'view-5' }"
              >
                Leer más...
              </router-link>
            </div>
            <hr class="my-10" />
          </div>
          <div
            class="xl:w-1/4 md:w-2/4 w-screen xl:px-0 md:px-10 px-16 xl:mx-20 md:mx-0 mx-0"
          >
            <div class="sm:text-6xl font-black text-indigo-900 text-5xl">
              5.6
            </div>
            <div class="text-xl font-bold text-indigo-900 py-5 title-header">
              Aplicaciones de buses
            </div>
            <div class="text-justify parrafo">
              Este es un bus unidireccional debido a que la información fluye es
              una sola dirección, de la CPU a la memoria o a los elementos de
              entrada y salida. La CPU sola puede colocar niveles lógicos en las
              n líneas de dirección, con la cual se genera 2n posibles
              direcciones diferentes. Cada una de estas direcciones corresponde
              a una localidad de la memoria o dispositivo de E / S.
            </div>
            <img
              class="fondo-2"
              src="https://2.bp.blogspot.com/-eg0JT8y9afE/WV49WWP_XkI/AAAAAAAAfMw/arREmR2AXbQ8TWo3B95SYVPQTQZJbQqoACLcBGAs/s1600/1.JPG"
              alt="wan"
            />
            <div class="py-5 text-center">
              <router-link
                class="hover:text-yellow-700 hover:bg-gray-300 transition duration-500 rounded-md border border-gray-600 shadow-sm px-4 py-3"
                :to="{ name: 'view-6' }"
              >
                Leer más...
              </router-link>
            </div>
            <hr class="my-10" />
          </div>
        </div>
        <div class="flex items-center justify-center">
          <div
            class="xl:w-1/4 md:w-2/4 w-screen xl:px-0 md:px-10 px-16 xl:mx-20 md:mx-0 mx-0"
          >
            <div class="sm:text-6xl font-black text-indigo-900 text-5xl">
              5.7
            </div>
            <div class="text-xl font-bold text-indigo-900 py-5 title-header">
              Comunicación
            </div>
            <div class="text-justify parrafo">
              Un conversor ADC puede convertir un voltaje en un número binario
              digital. Los conversores A/D son utilizados en cualquier lugar
              donde sea necesario procesar una señal, almacenarla o
              transportarla en forma digital.
            </div>
            <img
              class="fondo-2"
              src="https://revistadigital.inesem.es/gestion-integrada/files/2012/11/Red_comunicacion_industrial.jpg"
              alt="wan"
            />
            <div class="py-5 text-center ">
              <router-link
                class="hover:text-yellow-700 hover:bg-gray-300 transition duration-500 rounded-md border border-gray-600 shadow-sm px-4 py-3"
                :to="{ name: 'view-7' }"
              >
                Leer más...
              </router-link>
            </div>
            <hr class="my-10" />
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
<style scoped>
/* .image-size {
} */
.title-header {
  height: 100px;
}
.fondo-2 {
  margin: 10px;
  width: 200px;
}
.parrafo {
  height: 200px;
}

@media only screen and (max-width: 1200px) {
  .title-header {
    height: 130px;
  }
  .parrafo {
    height: 180px;
  }
}
</style>
