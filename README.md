# Actividad de laboratorio 3

> ## Objetivos
> * Comprender los conceptos básicos para realizar prototipado.
> * Familiarizarse con el hardware del laboratorio.



## Introducción

Simular es sumamente importante por que es el paso previo a prototipar; sin embargo, cuando se trabaja en electrónica no es sufienciente con la simulación simplemente pues, la vida real no es como el papel. Asi mismo, la escencia de este curso son las cosas. Las cosas en terminos de IoT constituyen la interfaz que conecta la arquitectura con el entorno. 

Para poder experimentar, en el laboratorio se disponen de unos sistemas de desarrollo y kits de entrenamiento para poder empezar a jugar con las cosas. En este laboratorio, nos centraremos en conocer y cacharrear con estos elementos para consolidar las bases necesarias el prototipado electrónico.

## Actividad previa

Abra el siguiente [link](https://sites.google.com/view/iniciacionarduino/c%C3%B3digo?authuser=0), observe y analice cada uno de los ejemplos que crea pertinentes.

## Herramientas del laboratorio

En el laboratorio hay un gran numero de herramientas, sin embargo, la siguiente tabla describe los elementos de hardware que usaremos en este laboratorio.

|Elemento|Descripción|
|--|--|
|Arduino Uno|Placa de desarrollo Arduino Uno ([link](https://docs.arduino.cc/hardware/uno-rev3))|
|Tarjeta de desarrollo ESP8266 NodeMCU WiFi Devkit|Tarjeta de desarrollo basada en ESP8266 ([link](NodeMCU-V3.pdf))|
|Base Shield V2| Base para facil conexión de componentes con el arduino uno ([link](https://wiki.seeedstudio.com/Base_Shield_V2/))|
|Grove Base Shield for NodeMCU V1.0|Tarjeta para conexión plug&play de componentes electronicos con la placa NodeMCU ([link](https://wiki.seeedstudio.com/Grove_Base_Shield_for_NodeMCU_V1.0/))|
|Grove - Starter Kit v3|Kit de desarrollo para prototipado rapido ([link](https://wiki.seeedstudio.com/Grove_Starter_Kit_v3/))|
|37 sensor kit Elegoo| Kit de sensores Elegoo para prototipado rapido ([link](http://spot.pcc.edu/~dgoldman/labs/37SENSORKIT.pdf))|
|AlphaBot2 robot building kit for Arduino/Pi/PiZero| Kit para prototipado de robots AlphaBot2 ([link](https://www.waveshare.com/wiki/AlphaBot2))|

## Prototipado parte 1 ##

### Componentes

1. Arduino Uno
2. Grove - Starter Kit

### Instrucciones

En esta primera parte del curso se explorar el uso del Grove - Starter Kit v3 para lo cual se sugiere seguir las instrucciones dadas en la documentación ([link](https://wiki.seeedstudio.com/Grove_Starter_Kit_v3/)) con el fin de explorar los diferentes ejemplos. La idea es que cada uno de los equipos de trabajo descargue un ejemplo diferentes y lo ponga a funcionar. Luego, haciendo un breve analisis del código explique brevemente a los demas grupos lo que hace el programa montado. 

Los codigos de los ejemplos a estudiar se encuentran en el siguiente repositorio: https://github.com/Seeed-Studio/Sketchbook_Starter_Kit_V2.0. Para no tener que codificar cada uno de estos ejemplos descargar la versión comprimida de este repositorio en una ubicación conocida y descomprimirlo (se recomienta que renombre el directorio de **Sketchbook_Starter_Kit_V2**, que ha sido descomprimido, de modo que se quede llamando **Sketchbook**).

Inicialmente es necesario identificar el esquema de conexión de la **Base Shield V2** ([link](https://wiki.seeedstudio.com/Base_Shield_V2/)) la cual se muestra a continuación:

![base_shield](https://files.seeedstudio.com/wiki/Base_Shield_V2/img/Base_Shield_v2-1.png)

La idea es que analice la parte de cada uno de los códigos de tal manera que pueda identificar los puertos que se emplean para conectar el arduino con los dispositivos electronicos a traves de la placa base.

A continuación se listan los ejemplos a montar (los cuales se pueden buscar en este directorio):

1. **Grove - LED**: File -> Sketchbook -> Grove_LED

![montaje_led](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-LED_Ex.jpg)

2. **Grove - Button**: File -> Sketchbook -> Grove_Button
   
![montaje_button](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-Button_Ex.jpg)

3. **Grove – Buzzer**: File -> Sketchbook -> Grove_Buzzer
   
![montaje_buzzer](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-Buzzer_Ex.jpg)

4. **Grove - Relay**: File -> Sketchbook -> Grove_Relay
   
![montaje_relay](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-Relay_Ex.jpg)

5. **Grove - Rotary Angle Sensor**: File -> Sketchbook -> Grove_Rotary_Angle_Sensor
   
![montaje_pot](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-Rotary_Angle_Sensor_Ex.jpg)

6. **Grove - Sound Sensor**: File -> Sketchbook -> Grove_Sound_Sensor
   
![montaje_sound](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-Sound_Sensor_Ex.jpg)


7. **Grove - Temperature Sensor**: File -> Sketchbook -> Grove_Temperature_Sensor
   
![montaje_temperature](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-Temperature_Sensor_Ex.jpg)

8. **Grove - Light Sensor**: File -> Sketchbook -> Grove_Light_Sensor
   
![montaje_light](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-Light_Sensor_Ex.jpg)

9. **Grove - Servo**: File -> Sketchbook -> Servo
   
![montaje_servo](https://files.seeedstudio.com/wiki/Grove_Starter_Kit_v3/img/Grove-Starter_Kit_Servo.jpg)


### Opcional 

Los fabricantes de kits de desarrollo suelen colocar las librerias con los diferentes drivers y ejemplos asociados. Para ver como instalar una libreria en arduino se sugiere ver el enlace [Installing Additional Arduino Libraries](https://www.arduino.cc/en/guide/libraries). Para el caso de los elementos del fabricante **seeed** se puede hacer una busqueda de librerias en el gestor del arduino IDE o buscar en el repositorio deseado y descargarlo comprimido y agregarlo a la biblioteca (ver [link](https://wiki.seeedstudio.com/How_to_install_Arduino_Library/)).














## Material de apoyo

Para esta sesión, nos basaremos en el siguiente material disponible en la web:
* [What is arduino?](https://learn.sparkfun.com/tutorials/what-is-an-arduino/introduction)
* [Intro to Arduino - Zero to Prototyping in a Flash!](https://cdn.sparkfun.com/assets/3/9/d/9/e/Intro_to_Arduino_-_v30_1.pdf)

## Conceptos previos

Se recomienda tener claro los siguientes conceptos:
* [How to Use a Breadboard](https://learn.sparkfun.com/tutorials/how-to-use-a-breadboard)
* [How to Read a Schematic](https://learn.sparkfun.com/tutorials/how-to-read-a-schematic/
)
* [How to Read a Datasheet](https://www.sparkfun.com/tutorials/223?_ga=2.220939870.716925408.1637633025-812475524.1634861735)
 
## Guia


## Enlaces
* https://www.youtube.com/watch?v=fCxzA9_kg6s&list=PLA567CE235D39FA84
* https://www.seeedstudio.com/Sidekick-Basic-Kit-for-Arduino-V2-p-1858.html
* https://wiki.seeedstudio.com/Sidekick_Basic_Kit_for_Arduino_V2/
* https://wiki.seeedstudio.com/Base_Shield_V2/
* https://github.com/marcinwisniowski/ElegooFritzingBin
* https://www.waveshare.com/wiki/AlphaBot2
* 
