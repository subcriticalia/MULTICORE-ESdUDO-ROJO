# MULTICORE-ESDUDO-ROJO
Diseñar la placa - ´Créalo tu mismo de coste más reducido para la Fpga CYC1000 con una bluepill STM32F103C8T6

[![Escudo ROJO](https://img.youtube.com/vi/kMc1XR39d8Y/maxresdefault.jpg)](https://youtu.be/kMc1XR39d8Y)


   Se muestra el multicore en desarrollo para cyc1000 de arrow/trenz el cual aloja una fpga Cyclone 10 LP de intel con 25kles y 66 bloques de Bram de 9Kbytes, tiene integrada una memoria de celular de bajo consumo y reducida latencia, siendo una sdram a 166Mhz con 8MBytes en un bus de 16bits, La familia Cyclone 10 LP permite implementar modelos que superan los 400Mhz en sus diseños, manteniendo un bajo consumo. 
También hay que disponer de una bluepill con un STM32F103C8Tx, posee 64Kbytes de Flash y 20Kbytes de sram, con una unidad de proceso ARM cortex M3 de 32bit funcionando a 72Mhz. 

   Este modelo implementa soluciones de muy baja latencia, al usar envoltorios con máquinas de estado finito para el video compuesto y el teclado.
   
###   https://github.com/TheSonders/COLOR_PAL
   
###   https://github.com/TheSonders/USBKeyboard

   El diseño es de reducido tamaño, permitiendo alojarlo en equipos estropeados y no recuperables.

   En precio asociado a la placa son aproximadamente 6€.

   Una lista de los pocos componentes necesarios:
  • 6 condensadores de filtrado, ramas serie y paralelo.
  • 4 resistencias. Dos de ellas prescindibles mediante programacion de pull down en las patillas K1 y L1 de la cyc1000.
  • 2 potenciometros de señal para ajustar la intensidad.
  • Asi como bastantes tiras de pines, machos y hembras también pines apilables usados en arduino.
  • Un condensador electrolítico.
  • Un pulsador.
  • Un puerto usb A.
  • Un puerto de vídeo compuesto.
  • Disponer de una muestra de cyc1000 del programa Europero de fpgas de intel/arrow.
  • Disponer de una bluepill.
  • Así como un módulo i2s de texas instruments MCP5102A.
 
   Es con diferencia el sistema multicore más económico.

Las placas necesarias:

BLUEPILL STM32F103C8T6:

https://es.aliexpress.com/item/1005002976480289.html

SD+TFT AZ-Delivery de 1,8Pulgadas:

https://es.aliexpress.com/item/1005005060814683.html

CYC1000 versión mejorada del 2023 TEI0003-03-QFCR4A-CYC1000:

https://shop.trenz-electronic.de/en/TEI0003-03-QFCR4A-CYC1000-with-Cyclone-10-FPGA-8-MB-SDRAM-8-MB-Flash-6.15-x-2.5-cm?c=480

O una muestra en el programa europeo de microfpgas:

https://www.arrow.com/en/family/intel-solutions-europe

Grupo de la iniciativa ATLAS en TELEGRAM:
https://t.me/INICIATIVAATLAS

Licencia:
https://ohwr.orgcern_ohl_s_v2.txt
