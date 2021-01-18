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
          5.6
        </div>
        <div class="text-xl font-bold text-indigo-900 py-5">
          Aplicaciones de buses
        </div>
      </div>

      <div class="text-justify">
        <p>
          Este es un bus unidireccional debido a que la información fluye es una
          sola dirección, de la CPU a la memoria o a los elementos de entrada y
          salida. La CPU sola puede colocar niveles lógicos en las n líneas de
          dirección, con la cual se genera 2n posibles direcciones diferentes.
          Cada una de estas direcciones corresponde a una localidad de la
          memoria o dispositivo de E / S. Los microprocesadores 8086 y 8088
          usados en los primeros computadores personales (PC) podían direccionar
          hasta 1 megabyte de memoria (1.048.576 bytes). Es necesario contar con
          20 líneas de dirección. Para poder manejar más de 1 megabyte de
          memoria, en los computadores AT (con procesadores 80286) se utilizó un
          bus de direcciones de 24 bits, permitiendo así direccionar hasta 16 MB
          de memoria RAM (16.777.216 bytes). En la actualidad los procesadores
          80386DX pueden direccionar directamente 4 gigabytes de memoria
          principal y el procesador 80486DX hasta 64 GB.
        </p>

        <h3><b>Bus de Datos</b></h3>
        <p>
          Este es un bus bidireccional, pues los datos pueden fluir hacia ó
          desde la CPU. Los m terminales de la CPU, de D0 - Dm-1, pueden ser
          entradas ó salidas, según la operación que se esté realizando (lectura
          o escritura). en todos los casos, las palabras de datos transmitidas
          tienen m bits de longitud debido a que la CPU maneja palabras de datos
          de m bits; del número de bits del bus de datos, depende la
          clasificación del microprocesador.
        </p>
        <p>
          En algunos microprocesadores, el bus de datos se usa para transmitir
          otra información además de los datos (por ejemplo, bits de dirección o
          información de condiciones). Es decir, el bus de datos es compartido
          en el tiempo o multiplexado. En general se adoptó 8 bits como ancho
          estándar para el bus de datos de los primeros computadores PC y XT.
          Usualmente el computador transmite un caracter por cada pulsación de
          reloj que controla el bus (bus clock), el cual deriva sus pulsaciones
          del reloj del sistema (system clock). Algunos computadores lentos
          necesitan hasta dos pulsaciones de reloj para transmitir un caracter.
          Los computadores con procesador 80286 usan un bus de datos de 16 bits
          de ancho, lo cual permite la comunicación de dos caracteres o bytes a
          la vez por cada pulsación de reloj en el bus. Los procesadores 80386 y
          80486 usan buses de 32 bits. El PENTIUM de Intel utiliza bus externo
          de datos de 64 bits, y uno de 32 bits interno en el microprocesador.
        </p>
        <h3><b>Bus de Control</b></h3>
        <p>
          Este conjunto de señales se usa para sincronizar las actividades y
          transacciones con los periféricos del sistema. Algunas de estas
          señales, como R / W, son señales que la CPU envía para indicar que
          tipo de operación se espera en ese momento. Los periféricos también
          pueden remitir señales de control a la CPU, como son INT, RESET, BUS
          RQ.
        </p>
        <p>
          Las señales más importantes en el bus de control son las señales de
          cronómetro, que generan los intervalos de tiempo durante los cuales se
          realizan las operaciones. Este tipo de señales depende directamente
          del tipo del microprocesador.
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
