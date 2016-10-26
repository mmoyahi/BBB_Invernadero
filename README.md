# BBB_Invernadero
Proyecto Invernadero: Usa un BBB como base para controlar un invernadero casero. Se controlan sensores y motores via internet o red local.

1._Se procurará estabelecer la comunicación via Wifi ESP8266 <-> BBB.
2._Se conectarán uno o más sensores por ESP8266
3._Se registraran parámetros como temperatura, humedad, tiempo de encendido de la bomba, tiempo de encendido de las lamparas.
4._Eventualmente estas mediciones serán graficadas por el BBB y subidas a un servidor propio (montado por el BBB y administrado por él)
5._Se podrán establecer una serie de parámetros via internet. Algunos ejemplos: humedad permitida*, temperatura máxima*, pedríodo de
encendido para la bomba.
*Es necesaraia la caracterización del sistema para poder conocer mejor estos parámetros.


2da. Fase
1._Se medirá la efectividad del sistema y tal vez los efectos que tiene la luz en la plantas mediendo el color verde en las hojas.
#Poco probable que la medición del color verde pueda medirse continuamente por la humedad del sistema, quizas una cámara externa y
 un algoritmo de procesamiento de imagenes podría ayudar.
