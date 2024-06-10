# SecurityFem
## Integrantes 
- Valeria Chavez Zarate
- Sandra Michel Hernández Chiquito

## Visión
Ayudar a las personas con un dispositivo portable el cual les aporte seguridad en cualquier momento, proporcionando el monitoreo constante de la ubicación y eventos de riesgo, de manera innovadora gracias a que se enviaran las alertas desde n dispositivo tan pequeño a contactos de emergencia.

## Software empleado
  
| Id | Software | Version | Tipo |
|----|----------|---------|------|
| 1  |Arduino   |2.0.1    |   IDE|
| 2  |Node-red  |3.0      |Servicio|
|3|Sqlite|3.46.0|SGBD|

## Epicas
* El llavero proporcionará monitoreo para la seguridad del usuario.
* Activación manual y remota de la alarma
* Geolocalización en tiempo real
* Gestión de Alertas y Notificaciones
* Registro de eventos del llavero en base de datos
* Comodidad y facilidad de uso

## Hardware empleado
| Id | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|-------------|--------|----------|-------------|
|   1|Pantalla táctil 2.4'' | Resolución de 240*320, color de 18 bits. Controlador spdf5408 con memoria RAM de vídeo integrada. |<img src="https://github.com/ItzelFuentes/SmartCar_Control/assets/108686186/9692adcf-d0c8-4b60-a0ec-93edf5e8dc08" width="400">|1|$200|
|   2| Cables de Puente de protoboard de Placa de Prueba| Es un elemento que permite cerrar el circuito eléctrico del que forma parte dos conexiones|<img src="https://user-images.githubusercontent.com/106613946/233218856-3a7458d8-7c8f-49eb-8914-3ab456faff30.png" width="400">|30|$60|
|   3|Buzzer| Es un dispositivo que tiene la capacidad de generar una señal de audio al ser alimentado|<img src="https://user-images.githubusercontent.com/106613946/233209389-17df52bd-0712-4ba0-9873-b426f1123213.png" width="400">|1|$27| 
|   4|Cable USB para Esp32| Cable USB que permite la alimentación y comunicación compatible con Esp32.|<img src="https://github.com/ItzelFuentes/SmartCar_Control/assets/108686186/36ffa2b7-0adc-48ec-9e8c-b3cbd7d995dd" width="400">|1|$25|
|   5|ESP32| El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos|![image](https://user-images.githubusercontent.com/104101668/214482867-90fbaa8c-7d6c-42f5-8a1c-004b815030a6.png)|1|$100|
|   6|Sensor pir| Sensor de movimiento que mide la luz infrarroja (IR) radiada de los objetos situados en su campo de visión. Puede ajustar el tiempo de activación de la salida (3s hasta 300s) y la sensibilidad del sensor (3m hasta 7m). Voltaje de alimentación: 4,5 a 20V.s|![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKKnnOEntjiumSKsJDve1lw4wgjg9jA9DcdA&s)|1|$60|
|   7|GPS NEO 6m| utiliza la tecnología de Ublox para brindar información de posicionamiento. También incluye una antena GPS de 25 x 25 mm, con conector UFL. Posee una pequeña batería y una memoria eeprom que permite guardar los últimos datos de posicionamiento y así lograr una detección más rápida.|![image](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/9f834ea8-b519-4b2a-94dc-2eca658eee1f)|1|$150|
|   8|Button| Es un control en el que el usuario puede hacer clic para proporcionar la entrada a una aplicación.|![image](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/e4bbc5f9-2081-4d47-8c3e-a7ab8ff7500d)|1|$4|

<!-- |   12|Protoboard|es prácticamente una PCB temporal con una forma y tamaño generalizados. Utilizada comúnmente para pruebas y prototipos temporales de circuitos|![image](https://user-images.githubusercontent.com/106613946/233217981-e8de4fd7-44f6-463f-b818-45785af1aeb5.png)|1|$0| 
|   13|Adaptador de fuente de alimentación de 12V 5A| Es un dispositivo electrónico comúnmente llamado fuente de alimentación, fuente de poder o fuente conmutada|![image](https://user-images.githubusercontent.com/106613946/233218241-90c26d7e-14da-4751-9295-47106387fa82.png)|1|$0| 
|   14| Módulo Relevadores Relay 4 Canales 5v | Puede controlar varios dispositivos y otros equipos con gran corriente: ideal para proyectos mecatrónicos. Este relevador soporta hasta 250 VAC o 30 VDC a 10 A.|![image](https://m.media-amazon.com/images/I/61dFbJu-y7L._SX522_.jpg)|1|$0|
-->

## Historias de usuario epicas
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
|  1 | Como  usuario que necesita mantener controlado el paradero, quiero poder rastrear la ubicación desde mi dispositivo móvil para poder ubicarla rápidamente en caso de emergencia.| Alta | 1-3 semanas|mediante el dashboard y la notificación de su paradero|Michel
|  2 |Como un usuario preocupado por la seguridad quiero recibir notificaciones en mi dispositivo móvil cuando se active la alarma en mi llavero para poder tomar medidas rápidas y apropiadas.| Alta | 1-3 semanas| Se deberá activar una alarma cuando el usuario presiona el botón de peligro y recibir notificación| Michel
|  3 |Como un usuario que necesita mantener un registro detallado de eventos relacionados con mi llavero quiero tener un registro  de  los eventos y acciones relacionadas con mi llavero inteligente para poder revisarlos y analizarlos en cualquier momento| Alta | 1-3 semanas|Se muestra en la base de datos y dashboard los eventos de los sensores |Valeria
|  4 |como usuario quiero poder activar y desactivar el sensor de movimiento en situaciónes de emergencia| Alta |1-3 semanas| solo cuando se preciona el boton se enciende y responde el sensor|Valeria


## Fotografía tomada del dibujo del prototipo propuesto por el equipo para el proyecto
![image](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/c3583f2f-afb4-43aa-a8fd-d61779214e6d)



## Arquitectura del proyecto
se solicita que contenga al menos los siguientes elementos: sensores, actuadores, controladores, plataforma de base de datos, protocolo de comunicación, gestión de energía, dispositivos receptores y/o transmisores, puede contener además elementos de nube, redes, seguridad, dispositivos pasivos, direccionalidad de comunicación.

## Captura de pantalla del tablero kanban para cada uno de los sprints del proyecto
En cada sprint se contemplan los siguientes tableros: Entrada, análisis, construcción, revisión y terminado.

| Sprint | Tablero Trello | 
|----|----------|
| 1  |![image](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/cfefe86b-be3c-49bd-bbb4-2070cc43bea2)|
| 2 |![image](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/20d48c73-fb41-4b76-8aa5-8516002c6533)|
| 3 ||



## Circuito diseñado para el proyecto completo 

![image](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/63695d0c-98ac-4840-82ef-a95e2a308be2)


## Resultados, screenshot de cada uno de los resultados del proyecto, con una descripción sintetizada
En los esta primera entrega se realizo un circuito el cual es capaz de detectar el movimiento y encender el buzzer integrado cada que lo detecta, de igual manera, se hace el envio de whatsApp.

![Imagen de WhatsApp 2024-06-08 a las 21 36 12_7ee26f1d](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/16a41716-6aed-4845-90b9-bfc0770cf8f7)

![image](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/2112e9c8-32e1-4ee2-8d41-086cf0d05fd3)

![image](https://github.com/HernandezChiquitoSandra/SecurityFem/assets/107783594/c1e0d249-c97c-4745-ba35-a46c36653338)


