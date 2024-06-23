esptool.py -p /dev/ttyUSB0 write_flash -fm dout 0x0000 esp8266_deauther.ino.nodemcu.bin/dev/ttyUSB0write_flash-fm doutesp8266_deather.ino.nodemcu.bin

#comando para flashear , Con la NodeMCU (o cualquier placa de desarrollo similar)
, la ubicación del flash es 0x0000 y el modo es dout.

Donde está el puerto COM de su dispositivo, le dice al programa que escriba
 en la memoria flash, es el modo flash y es el nombre de su archivo .bin
