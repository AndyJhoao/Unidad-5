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
          5.1
        </div>
        <div class="text-xl font-bold text-indigo-900 py-5">
          Tipos de Puertos
        </div>
      </div>

      <div class="text-justify">
        <h3><b>Puertos de Entrada y Salida en un Microcontrolador.</b></h3>
        <p>
          Cualquier aplicación de un sistema digital basado en un
          microprocesador o microcontrolador requiere la transferencia de datos
          entre circuitos externos al microprocesador y él mismo. Estas
          transferencias constituyen las operaciones llamadas ENTRADA y SALIDA,
          (I/O).
        </p>
        <img
          class="info-image"
          src="https://creatoz.eu/wp-content/uploads/69194380c15d910518319b3ce41ca9e0.jpeg"
          alt=""
          style="width: 600px;"
        />
        <p>
          Los puertos de entrada/salida son básicamente registros externos o
          internos. Algunos microprocesadores proporcionan señales de control
          que permiten que los registros externos que forman los puertos de E/S
          ocupen un espacio de direcciones separada, es decir, distinto del
          espacio de direcciones de los registros externos que componen la
          memoria, por tanto, estos registros tienen que poder ser
          direccionables por el procesador.
        </p>
        <p>
          Cuando los puertos tienen asignado un espacio de direcciones separado,
          se dice que están en modo de E/S AISLADA o ESTÁNDAR. Por el contrario,
          cuando se ubican dentro del mismo espacio que la memoria, se dice que
          están en modo de E/S MAPEADA A MEMORIA o PROYECTADA EN MEMORIA. El
          direcciomanieto varía según la arquitectura del procesador.
        </p>

        <h3><b>E/S Aislada (isolated I/O).</b></h3>
        <p>
          Para que un microprocesador pueda implementar el modo E/S aislada
          (isolated I/O) son indispensables las siguientes condiciones:
        </p>
        <ul>
          <li class="ul-element">
            1. El microprocesador debe proporcionar señales de control que
            permitan distinguir entre una operación con un puerto y una
            referencia a memoria.
          </li>
          <li class="ul-element">
            2. El código de instrucciones debe tener instrucciones especiales
            con las que se pueda leer (entrada) o escribir (salida) en los
            puertos.
          </li>
        </ul>
        <p>
          La CPU trata los registros de los dispositivos de E/S como posiciones
          de memoria, utilizando las mismas instrucciones para acceso a memoria
          y a dispositivos de E/S. Con este esquema, una parte del mapa de
          memoria del sistema es reservado para E/S en lugar de para memoria,
          asignado las direcciones en ese rango a los distintos dispositivos de
          E/S. De esta forma, existe un único espacio de direcciones en el
          sistema, que se emplea tanto para la memoria principal como para la
          E/S. La ventaja es su sencillez, ya que no es necesario implementar
          instrucciones ni circuitería especial para la E/S. Esta alternativa se
          utiliza sobre todo en arquitecturas RISC y sistemas empotrados.
          Ejemplos de sistemas que utilizan esta aproximación son la familia de
          procesadores PowerPC de IBM y la familia de procesadores MIPS.
        </p>
        <img
          class="info-image"
          src="https://3.bp.blogspot.com/-NA3pCIQAluo/T4JYog7SIvI/AAAAAAAAAKI/nA7tacsloA4/s1600/aislado.png"
          alt=""
        />
        <h3><b>E/S Mapeada (Memory mapped I/O).</b></h3>
        <p>
          El modo de E/S mapeada a memoria (Memory mapped I/O) se basa en que
          tanto las localidades de memoria como los puertos de E/S se consideran
          como registros externos desde el punto de vista del microprocesador.
          Entonces, las instrucciones que hacen referencia a la memoria también
          pueden transferir datos entre un dispositivo periférico y el
          microprocesador, siempre y cuando el puerto de E/S que los
          interconecta se encuentre dentro del espacio de direccionamiento de
          memoria, es decir, controlado por las señales de control para memoria.
          De esta forma, el registro asociado con el puerto de E/S es tratado
          simplemente como una localidad de memoria más.
        </p>
        <img
          src="https://image.slidesharecdn.com/4-150825124244-lva1-app6892/95/entrada-y-salida-11-638.jpg?cb=1440506585"
          alt=""
        />
        <p>
          En este caso se mantienen espacios de direcciones diferentes para
          memoria y E/S, disponiendo el procesador de instrucciones especiales
          para el acceso a direcciones de E/S, distintas a las de acceso a
          memoria. Al tener los dispositivos de E/S un mapa de memoria separado
          de la memoria principal, la CPU utiliza una señal de control (M/IO)
          para indicar si la dirección que está en el bus de memoria es de E/S,
          o bien se utiliza un bus de E/S propio. Ejemplos de sistemas que usan
          esta aproximación son la familia de procesadores x86 de Intel.
        </p>
        <img
          class="info-image"
          src="https://tech4gamers.com/wp-content/uploads/2015/12/Intel_Skylake.jpg"
          alt=""
        />
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
  width: 200px;
}
</style>
