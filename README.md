# PersonajeNavidenio
## Nombre del Personaje 
Pastorcita con cesta de frutas
## Materiales Utilizados
|Nombre|Descripción|Cantidad|Precio|
|--|--|--|--|
|ESP32|Microcontrolador con acceso WiFi y Bluetooth|1|$140.00|
|Cables Dupoint|Cables para conectar circuito|50|$40.00|
|Micro Motor Electrico|Para el movimiento de la canasta|1|$60.00|
|Buzzer Pasivo ARD-356|Para reproducir música navideña|1|$5.00|
|Batería Recargable|Para la alimentación|1|$45.00|
|LED ROJO|Iluminación decorativa de las frutas|1|$3.00|
|LED AMARILLO|Iluminación decorativa de las frutas|2|$3.00|
|LED NARANJA|Iluminación decorativa de las frutas|2|$3.00|
|LED VERDE|Iluminación decorativa de las frutas|2|$3.00|
|PROTOBOARD DE 170 PUNTOS|Conección de todos los componentes a la placa|1|$30.00|
|Sensor Ultrasonico HC-SR04|El HC-SR04 es un sensor ultrasónico, este utiliza el sonar para determinar la distancia a un objeto|1|$22.00|


## Software Utilizado
|Nombre|Version|Tipo|
|--|--|--|
|Arduino|2.2.1|Software Libre|

## Prototipo en dibujo
A continuación, se muestra un boceto del diseño de la pastora con cesta de frutas:
![Prototipo](https://github.com/elizabethgutierrez27/PersonajeNavidenio/assets/146129308/d56e73bf-ea01-4aa6-8767-e47a694e4ec7)

## Comunicación 
El dispostivo se va a comunicar con el telefono para controlar el movimiento, el encendido de las luces led y de la musica navideña.
El proyecto es una pastora con una cesta de frutas, esta tendra luz en su cesta, donse se aplicara a darle la luz con los leds dependiendo el clor de la fruta. El sonido se mostrara en la manera de que suene un villancico o una musica navideña en el interior de la pastora, esta sera mediante un buzzer y/o una bocina y tendra conectado un sensor de sonido ultrasonico para que suene cuando sienta presencia cercana y dejara de sonar cuando se lejen, este sera controlado por el dispositivo, que en este caso sera el telefono. El movimiento se reflejara al momento de que la pastora levante la cesta y la mueva en direccion pensular.
La programación y la comunicación se reflejara al momento de programar cada uno de los dispositivos controlados mediante el telefono celular.

## Arquitectura
Los componentes utilizados (el microprosesador, los sensores, acceadores y acceso a los datos)
1. Parte de la canasta donde los leds representan el color de las frutas dentro de ella.
   ![Canasta](https://github.com/elizabethgutierrez27/PersonajeNavidenio/assets/146129308/aa1602d0-3a10-4a6e-be21-6844e547c4e2)
   
3. Demostración del circuito correspondiente al sensor ultrasonico y el buzzer, que se utilizara para reproducción de un villancico navideño.
   
   ![image](https://github.com/elizabethgutierrez27/PersonajeNavidenio/assets/146129308/ae45f99f-5e1b-4b59-bbf1-6c747eddcdd3)


## Bases de Datos
Gestor de la base de datos, tablas.

![image](https://github.com/elizabethgutierrez27/PersonajeNavidenio/assets/146129308/c054ae21-b88b-452c-901d-82bfb3486ace)

## Archivos Proyecto
https://drive.google.com/drive/folders/1swOee1ue7QOkj5y9GojLmF9AORHWIu1Z?usp=sharing

## Imagenes y videos proyecto
![Pastora](https://github.com/elizabethgutierrez27/PersonajeNavidenio/assets/146129308/4d8189ef-38ac-4909-ab2b-d26341b13111)

https://drive.google.com/file/d/1Zy2ZXfB6Q0CttPq7N4ZiZPpsBcU2wzYU/view?usp=sharing

https://drive.google.com/file/d/1Yw8CTWWVEYgetRTsgNb-hO_3gt7yaXbh/view?usp=sharing






