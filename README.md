# WRO-2024

![logo](https://github.com/ROBOTICAIPTC/New_Line/blob/main/other/logo-new-line.jpeg)


# Contenido
* [**Detalles del equipo**](#DETALLES-DEL-EQUIPO)
* [**Photos**](#photos)
  * [Team Photos](#team-photos )
  * [Vehicle Photos](#vehicle-photos)
* [**Performance Videos**](#RONDA-DE-DESAFIO)
* [**Gestion de energia y los sentidos**](#GESTION-DE-ENERGIA-Y-LOS-SENTIDOS)
* [**Gestion de energia**](#GESTION-DE-ENERGIA)
* [**Gestion de Movilidad**](#GESTION-DE-MOVILIDAD)
* [**Controlador/Robot**](#CONTROLADOR/ROBOT)
* [**Sensores y margenes de error**](#SENSORES-Y-MARGENES-DE-ERROR)
* [**Recomendaciones y tips**](#RECOMENDACIONES-Y-TIPS)
* [**Diagrama**](#DIAGRAMA)
* [**Version del progama**](#VERSION-DEL-PROGAMA)
    
    
  
   # Detalles del equipo

Nombre del equipo: New Line

País: Panamá, Panamá Oeste, Distrito de Capira

Miembros del equipo: Josué Jiménez e Isaac Clara

Coach: Mara Martínez
</div>
Este repositorio presenta información detallada sobre la construcción del robot del equipo New Line, el cual participa en la competencia WRO-FUTURE ENGINEERS de la temporada mundial WRO Panamá 2024. 
</div>

# Photos

* `t-photos` contiene 2 fotos del equipo (una oficial y una foto divertida con todos los miembros del equipo)
  
# Team-Photos

-Foto Formal
![equipo](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/20240702_122028.png)

- Foto Divertida
![divertida](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/13.jpg)

- Codificando
![15](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/15.jpg)

* `v-photos` contiene 6 fotos del vehículo (de cada lado, desde arriba y desde abajo)

# Vehicle-Photos

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

# Ronda de desafio abierto
https://youtu.be/KI8TZq1QNDs

* `schemes` contiene uno o varios diagramas esquemáticos en formato JPEG, PNG o PDF de los componentes electromecánicos que ilustran todos los elementos (componentes electrónicos y motores) utilizados en el vehículo y cómo se conectan entre sí.

# GESTION DE ENERGIA Y LOS SENTIDOS

CONEXION A	
Motor Grande: Este componente esencial facilita el movimiento de las llantas traseras del robot, proporcionando la potencia y precisión necesarias para maniobrar con eficiencia en diversas superficies y condiciones.

CONEXION B	
Motor Mediano: Este motor permite que el robot gire y cambie de dirección, facilitando movimientos precisos hacia la izquierda y la derecha, y contribuyendo a una mayor maniobrabilidad y control en su desplazamiento.

CONEXION 4	
Sensor Ultrasónico: Este sensor permite al robot detectar objetos a diferentes distancias y utiliza esta información para determinar el momento adecuado para determinar los cambios de dirección, garantizando así la seguridad y la precisión en sus movimientos.

CONEXION 3	
Sensor de Color: Este sensor permite detectar los colores de los cubos en color rojo y verde de la pista perimitiendo que el robot decida hacia que lado debe girar 

# GESTION DE ENERGIA

El bloque EV3 y todo el vehículo obtienen su energía de una batería recargable de litio de 10 V. Esta fuente de energía es fundamental para el funcionamiento continuo del sistema, ya que proporciona la electricidad necesaria para todos los componentes del robot. Dentro del bloque EV3, la administración de energía es compleja y eficiente, involucrando múltiples regulaciones de conmutación que están estrictamente controladas y entrelazadas. Estas regulaciones aseguran que el circuito electrónico arranque correctamente y mantenga un funcionamiento estable.

Para proteger el bloque EV3 de posibles cortocircuitos, se han implementado tres interruptores de polietileno estratégicamente ubicados. Dos de estos interruptores están dedicados a los controladores de motor, mientras que el tercero protege el resto del circuito. Cada uno de estos interruptores poligonal tiene una corriente de retención de aproximadamente 1,1 A, y se activa cuando la corriente alcanza aproximadamente 2,2 A. Este diseño de protección garantiza que cualquier sobrecarga potencial en el sistema sea rápidamente gestionada, evitando daños a los componentes y asegurando una operación segura y confiable del robot.

Estos mecanismos de protección no solo prolongan la vida útil del bloque EV3, sino que también mejoran la eficiencia del sistema, permitiendo que los motores y otros componentes electrónicos funcionen de manera óptima sin riesgo de fallos eléctricos. La inclusión de estos interruptores de polietileno es una muestra del enfoque detallado y meticuloso en el diseño del sistema de administración de energía del EV3, asegurando que cada parte del robot reciba la cantidad adecuada de energía y esté protegida contra cualquier eventualidad eléctrica

# GESTION DE MOVILIDAD 


La selección del motor es un componente crucial en el sistema de navegación autónoma de nuestro vehículo. El kit LEGO MINDSTORMS EV3 ofrece dos opciones distintas de motor: motores grandes y motores medianos. Estos motores son fundamentales para el rendimiento del vehículo, cada uno con características específicas que se ajustan a diferentes necesidades del proyecto.

Después de una cuidadosa evaluación de las necesidades específicas de nuestro proyecto, optamos por implementar un motor grande para accionar las llantas traseras del vehículo. Esta decisión se basa en varias consideraciones clave. En primer lugar, el motor grande del LEGO EV3 proporciona una potencia considerable, capaz de mover el vehículo con eficacia incluso en condiciones de alta fricción o resistencia en la pista. Además, la precisión del motor grande facilita una maniobrabilidad controlada, lo cual es esencial para que el vehículo navegue con exactitud por el circuito. Estos motores grandes son conocidos por su capacidad para soportar cargas más pesadas y proporcionar un par motor superior, lo que es crucial para mantener la estabilidad y velocidad del vehículo durante la competencia.

Por otro lado, decidimos utilizar un motor mediano para las funciones de giro y cambio de dirección del vehículo. Este motor mediano, también parte del set LEGO EV3, es ideal para ejecutar movimientos precisos hacia la izquierda y la derecha, lo que contribuye a una mayor maniobrabilidad y control en el desplazamiento del robot. La capacidad del motor mediano para realizar ajustes finos en la dirección es fundamental para evitar obstáculos y seguir las indicaciones del sensor de color, que determina el rumbo del vehículo basado en los colores detectados en la pista. Los motores medianos son más ligeros y compactos, lo que facilita su integración en el diseño del vehículo sin añadir peso innecesario.

Adicionalmente, ambos tipos de motores están equipados con sensores de rotación incorporados, que permiten un control preciso de la velocidad y la posición. Esta característica es especialmente útil para la programación de secuencias de movimiento exactas, garantizando que el vehículo siga el trayecto planificado sin desviaciones.

*El Motor grande funciona a 160–170 rpm, con un torque de rotación de 20 Ncm y un torque de rotor bloqueado de 40 Ncm. 
*El Motor mediano funciona a 240–250 rpm, con un torque de rotación de 8 Ncm y un torque de rotor bloqueado de 12 Ncm.

# CONTROLADOR/ROBOT

Procesador: ARM9, 300 MHz.

Memoria RAM: 64 MB.

Almacenamiento: 16 MB de memoria flash y ranura para tarjeta microSD de hasta 32 GB.

Sistema Operativo:  Kendel Linux.

Voltaje de Funcionamiento: 6-9V DC.

Batería Recargable: Batería de ion de litio EV3 (10V).

Duración de la Batería: Aproximadamente 6 horas con uso continuo de la batería recargable.

# SENSORES Y MARGENES DE ERROR

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

# RECOMENDACIONES Y TIPS                                                                                                                                                                                       

**Optimización de Energía**

*Usa la batería recargable de ion de litio para obtener una vida útil más larga y un rendimiento más constante.

*Apaga los motores y sensores cuando no estén en uso para ahorrar energía.

**Calibración de Sensores**

*Asegúrate de calibrar el sensor de color en las condiciones de luz del entorno de la competencia.

*Realiza pruebas para determinar la precisión del sensor ultrasónico y ajustar las distancias de seguridad en el código.

**Progamacion**

*Divide tu código en módulos para facilitar la depuración.

*Usa bucles y condicionales para gestionar las decisiones del robot en tiempo real.

*Implementa una rutina de reinicio en caso de que el robot se desvíe de su ruta prevista.

**Pruebas y ajustes**

*Realiza numerosas pruebas en el circuito real para ajustar los parámetros del sensor y los motores.

*Ajusta las velocidades de los motores para encontrar un equilibrio entre velocidad y precisión en los giros.

**Construccion fisica**

*Asegúrate de que todos los componentes estén firmemente conectados para evitar desconexiones durante la competencia.

*Usa engranajes y estructuras reforzadas para mejorar la estabilidad del robot.                                        

# DIAGRAMA 

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

 # VERSION DEL PROGAMA

Lego Mindstorms EV3

v.1.5.3

https://education.lego.com/en-us/downloads/mindstorms-ev3/software/

* `models` es para los archivos de modelos utilizados por impresoras 3D, máquinas de corte por láser y máquinas CNC para producir los elementos del vehículo. Si no hay nada que agregar a esta ubicación, se puede eliminar el directorio.


* `other` es para otros archivos que pueden usarse para entender cómo preparar el vehículo para la competencia. Puede incluir documentación sobre cómo conectarse a un SBC/SBM y cargar archivos allí, conjuntos de datos, especificaciones de hardware, descripciones de protocolos de comunicación, etc. Si no hay nada que agregar a esta ubicación, se puede eliminar el directorio.
