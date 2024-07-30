**
**Bienvenidos al repositorio oficial del equipo New Line de Panamá. Este repositorio alberga toda la documentación técnica y los materiales de ingeniería correspondientes al diseño y desarrollo de nuestro vehículo autónomo, que participará en el concurso WRO Future Engineers para la temporada 2024.**

![logo](https://github.com/ROBOTICAIPTC/New_Line/blob/main/other/logo-new-line.jpeg)

# DETALLES DEL EQUIPO

Nombre del equipo: New Line

País: Panamá, Panamá Oeste, Distrito de Capira

Miembros del equipo: Josué Jiménez e Isaac Clara

Coach: Mara Martínez

====

Este repositorio presenta información detallada sobre la construcción del robot del equipo New Line, el cual participa en la competencia WRO-FUTURE ENGINEERS de la temporada mundial WRO Panamá 2024. 

## Contenido

* `t-photos` contiene 2 fotos del equipo (una oficial y una foto divertida con todos los miembros del equipo)

- Foto Formal
![equipo](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/20240702_122028.png)

- Foto Divertida
![divertida](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/13.jpg)

- Codificando
![15](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/15.jpg)

* `v-photos` contiene 6 fotos del vehículo (de cada lado, desde arriba y desde abajo)

- Superior
![Superior](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Superior.jpg)

- Frontal
![Frontal](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Frontal.jpg)

- Posterior
![Posterior](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Posterior.jpg)

- Derecha
![Derecha](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Derecha.jpg)

- Izquierda
![Izquierda](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Izquierda.jpg)

- Inferior
![Inferior](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Inferior.jpg)

- Primera fase de armado
![Primer-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Primer-Armado.jpg)

- Segunda fase de armado
![Segundo-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Segundo-Armado.jpg)

- Tercera fase de armado
![Tercer-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Tercer-Armado.jpg)

- Base del ultrasonico
![18](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/18.jpg)

- Finalizando Armado
![17](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/17.jpg)

- Rescontrucción en pista
![20](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/20.jpg)

- Pruebas de Programacion
![21](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/21.jpg)

- Pruebas en simulador de aerodinamica
![22](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/22.jpg)


* `video` contiene el archivo video.md con el enlace a un video donde existe una demostración de manejo

- Ronda de Desafio Abierto https://youtu.be/KI8TZq1QNDs

* `schemes` contiene uno o varios diagramas esquemáticos en formato JPEG, PNG o PDF de los componentes electromecánicos que ilustran todos los elementos (componentes electrónicos y motores) utilizados en el vehículo y cómo se conectan entre sí.


CONTROLADOR/ROBOT

Procesador: ARM9, 300 MHz.

Memoria RAM: 64 MB.

Almacenamiento: 16 MB de memoria flash y ranura para tarjeta microSD de hasta 32 GB.

Sistema Operativo:  Kendel Linux.

VOLTAJES Y BATERIAS 

Voltaje de Funcionamiento: 6-9V DC.

Batería Recargable: Batería de ion de litio EV3 (7.2V, 2050 mAh) o 6 pilas AA (9V).

Duración de la Batería: Aproximadamente 6 horas con uso continuo de la batería recargable.

SENSORES Y MARGENES DE ERROR

Sensor de Color:
Precisión: ±1%
Modos: Color, Reflejo de Luz, Luz Ambiental
Margen de Error: Depende de la calidad de la luz y el color del objeto, puede variar pero generalmente dentro de ±5%.

Sensor Ultrasónico:
Rango: 3 cm a 255 cm.
Precisión: ±1 cm.
Margen de Error: Puede ser mayor en condiciones de alta interferencia acústica.

MOTORES 

Motor Grande (Large Motor):
Torque: 40 N.cm (Newton-centímetros)
RPM: 160-170

Motor Mediano (Medium Motor):
Torque: 8 N.cm
RPM: 240-250

RECOMENDACIONES Y TIPS                                                                                                                                                                                                                                                                                                    Optimización de Energía

*Usa la batería recargable de ion de litio para obtener una vida útil más larga y un rendimiento más constante.

*Apaga los motores y sensores cuando no estén en uso para ahorrar energía.

*Calibración de Sensores

*Asegúrate de calibrar el sensor de color en las condiciones de luz del entorno de la competencia.

*Realiza pruebas para determinar la precisión del sensor ultrasónico y ajustar las distancias de seguridad en el código.

PROGRAMACION 

*Divide tu código en módulos para facilitar la depuración.

*Usa bucles y condicionales para gestionar las decisiones del robot en tiempo real.

*Implementa una rutina de reinicio en caso de que el robot se desvíe de su ruta prevista.

PRUEBAS Y AJUSTES

*Realiza numerosas pruebas en el circuito real para ajustar los parámetros del sensor y los motores.

*Ajusta las velocidades de los motores para encontrar un equilibrio entre velocidad y precisión en los giros.

CONSTRUCCION FISICA 

*Asegúrate de que todos los componentes estén firmemente conectados para evitar desconexiones durante la competencia.

*Usa engranajes y estructuras reforzadas para mejorar la estabilidad del robot.                                        

![S1](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide1.JPG)

![S2](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide2.JPG)

![S3](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide3.JPG)

![S4](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide4.JPG)

![S5](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide5.JPG)

![S6](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide6.JPG)

![S7](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide7.JPG)

![S8](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide8.JPG)

![S9](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide9.JPG)

![S10](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide10.JPG)

* `src` contiene código de software de control para todos los componentes que fueron programados para participar en la competencia

Programa utilizado para codificar

Lego Mindstorms EV3

v.1.5.3

https://education.lego.com/en-us/downloads/mindstorms-ev3/software/

* `models` es para los archivos de modelos utilizados por impresoras 3D, máquinas de corte por láser y máquinas CNC para producir los elementos del vehículo. Si no hay nada que agregar a esta ubicación, se puede eliminar el directorio.


* `other` es para otros archivos que pueden usarse para entender cómo preparar el vehículo para la competencia. Puede incluir documentación sobre cómo conectarse a un SBC/SBM y cargar archivos allí, conjuntos de datos, especificaciones de hardware, descripciones de protocolos de comunicación, etc. Si no hay nada que agregar a esta ubicación, se puede eliminar el directorio.
