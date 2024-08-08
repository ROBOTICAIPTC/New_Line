# WRO-2024
 
  # Detalles del equipo

Nombre del equipo: New Line

País: Panamá, Panamá Oeste, Distrito de Capira

Miembros del equipo: Josué Jiménez e Isaac Clara

Coach: Mara Martínez

# Contenido
* [**Detalles del equipo**](#DETALLS-DEL-EQUIPO)
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

# Introduccion 

-New Line es un robot construido con el kit robótico EV3 Mindstorms. Utiliza sensores ultrasónicos y de color para evadir obstáculos de manera eficiente. Los motores para dirección y movilidad están ubicados en el eje delantero y trasero, respectivamente, lo que permite una maniobrabilidad precisa. El movimiento del robot se realiza mediante un sistema de tuercas, impulsando su eje trasero para proporcionar tracción y velocidad.

-El proceso de movimiento de New Line implica la recepción de datos continuos de sus sensores, que son procesados por su unidad central para tomar decisiones en tiempo real. Cuando el sensor ultrasónico detecta un obstáculo, el robot calcula una ruta alternativa para evitarlo. Simultáneamente, los sensores de color monitorean el entorno para asegurarse de que el robot no se salga de los límites de la pista.

# Materiales 

- 4 Rim Wide 43,2x26 W 6 Hol.0 4.8
- 4 Tyre Low Wide 056 X 28
- 5 Tube, W/ Double 4.85 Hole
- 2 Gear Wheel Z24
- 2 Gear Wheel 40T
- 1 Gear Wheel Z16
- 1 Technic Angular Wheel
- 6 Bush For Cross Axel 
- 2 Bion. Eye
- 5 Angular Beam 90° W.4 Snaps
- 8 Technic 13M Beam 
- 2 Beam Frame 5x7 04.85
- 4 Technic Angular Beam 3x7
- 6 Technic 3M Beam
- 2 Hto V Beam 90°
- 59 Connector Peg W. Friction
- 9 Connector Peg W, Friction 3M
- 12 Conn.Bush W.Fric/Cross Axle 
- 4 Technic 5M Beam 
- 2 Technic 11M Beam 
- 1 Technic 15M Beam 
- 6 Beam 3 M. W/4 Snaps 
- 2 Cross Block 3 M 
- 2 Technic Ang. Beam 3X5 90°
- 1 Rack 13m
- 1 Cross Axle 25M
- 1 Cross Axle 12M
- 2 Cross Axle 9M
- 5 EV3 Cable 250 Mm
- 2 EV3 Color Sensor
- 1 EV3 Ultrasonic Sensor 
- 1 Ms-EV3 Rechargea. Battery
- 1 P-Brick
- 1 Medium Motor
- 1 Large Motor 

# Gestion de movilidad

La selección del motor es un componente crucial en el sistema de navegación autónoma de nuestro vehículo. El kit LEGO MINDSTORMS EV3 ofrece dos opciones distintas de motor: motores grandes y motores medianos. Estos motores son fundamentales para el rendimiento del vehículo, cada uno con características específicas que se ajustan a diferentes necesidades del proyecto.

Después de una cuidadosa evaluación de las necesidades específicas de nuestro proyecto, optamos por implementar un motor grande para accionar las llantas traseras del vehículo. Esta decisión se basa en varias consideraciones clave. En primer lugar, el motor grande del LEGO EV3 proporciona una potencia considerable, capaz de mover el vehículo con eficacia incluso en condiciones de alta fricción o resistencia en la pista. Además, la precisión del motor grande facilita una maniobrabilidad controlada, lo cual es esencial para que el vehículo navegue con exactitud por el circuito. Estos motores grandes son conocidos por su capacidad para soportar cargas más pesadas y proporcionar un par motor superior, lo que es crucial para mantener la estabilidad y velocidad del vehículo durante la competencia.

Por otro lado, decidimos utilizar un motor mediano para las funciones de giro y cambio de dirección del vehículo. Este motor mediano, también parte del set LEGO EV3, es ideal para ejecutar movimientos precisos hacia la izquierda y la derecha, lo que contribuye a una mayor maniobrabilidad y control en el desplazamiento del robot. La capacidad del motor mediano para realizar ajustes finos en la dirección es fundamental para evitar obstáculos y seguir las indicaciones del sensor de color, que determina el rumbo del vehículo basado en los colores detectados en la pista. Los motores medianos son más ligeros y compactos, lo que facilita su integración en el diseño del vehículo sin añadir peso innecesario.

Adicionalmente, ambos tipos de motores están equipados con sensores de rotación incorporados, que permiten un control preciso de la velocidad y la posición. Esta característica es especialmente útil para la programación de secuencias de movimiento exactas, garantizando que el vehículo siga el trayecto planificado sin desviaciones.

*El Motor grande funciona a 160–170 rpm, con un torque de rotación de 20 Ncm y un torque de rotor bloqueado de 40 Ncm. 
*El Motor mediano funciona a 240–250 rpm, con un torque de rotación de 8 Ncm y un torque de rotor bloqueado de 12 Ncm.

# Gestion de energia

El bloque EV3 y todo el vehículo obtienen su energía de una batería recargable de litio de 10 V. Esta fuente de energía es fundamental para el funcionamiento continuo del sistema, ya que proporciona la electricidad necesaria para todos los componentes del robot. Dentro del bloque EV3, la administración de energía es compleja y eficiente, involucrando múltiples regulaciones de conmutación que están estrictamente controladas y entrelazadas. Estas regulaciones aseguran que el circuito electrónico arranque correctamente y mantenga un funcionamiento estable.

Para proteger el bloque EV3 de posibles cortocircuitos, se han implementado tres interruptores de polietileno estratégicamente ubicados. Dos de estos interruptores están dedicados a los controladores de motor, mientras que el tercero protege el resto del circuito. Cada uno de estos interruptores poligonal tiene una corriente de retención de aproximadamente 1,1 A, y se activa cuando la corriente alcanza aproximadamente 2,2 A. Este diseño de protección garantiza que cualquier sobrecarga potencial en el sistema sea rápidamente gestionada, evitando daños a los componentes y asegurando una operación segura y confiable del robot.

Estos mecanismos de protección no solo prolongan la vida útil del bloque EV3, sino que también mejoran la eficiencia del sistema, permitiendo que los motores y otros componentes electrónicos funcionen de manera óptima sin riesgo de fallos eléctricos. La inclusión de estos interruptores de polietileno es una muestra del enfoque detallado y meticuloso en el diseño del sistema de administración de energía del EV3, asegurando que cada parte del robot reciba la cantidad adecuada de energía y esté protegida contra cualquier eventualidad eléctrica

# Diagrama

![S1](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide1.JPG)

![S2](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide2.JPG)

![S3](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide3.JPG)

![S4](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide4.JPG)

![S5](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide5.JPG)

![S6](https://github.com/ROBOTICAIPTC/New_Line/blob/main/schemes/Slide6.JPG)

![image](https://github.com/user-attachments/assets/21156e77-72e8-4606-bc2e-5efd25ec5a41)

# Instrucciones del armado

FASE 1: Montaje de la estructura base
En esta primera fase, nuestro principal objetivo fue construir una base sólida que sirviera como cimiento para el resto del robot. La estabilidad es fundamental para cualquier robot móvil, por lo que comenzamos utilizando bloques y conectores robustos, seleccionados específicamente por su capacidad para resistir el peso y la tensión durante el movimiento. Nos aseguramos de que la base proporcionara un espacio equitativo y bien distribuido para las llantas en ambos ejes, tanto frontal como trasero, lo cual es crucial para mantener un equilibrio óptimo durante la operación. Además, se prestó especial atención a la simetría de la estructura, garantizando que cada componente estuviera alineado correctamente para evitar cualquier inclinación o desbalance que pudiera afectar el desempeño del robot en el circuito.

FASE 2: Instalación del motor grande
Con la base ya montada, procedimos a la instalación del motor grande, que es esencial para impulsar el movimiento del robot. Este motor fue seleccionado por su capacidad para proporcionar un par elevado, lo que permite una aceleración eficiente y una velocidad constante. El motor se acopló directamente al eje trasero del robot, asegurando que la potencia se transmita de manera eficiente a las llantas traseras. Para ello, diseñamos y ensamblamos un circuito de tuercas que permite una transferencia óptima de la potencia, minimizando la pérdida de energía y garantizando un movimiento fluido. Además, se implementaron piezas de color amarillo para estabilizar las llantas, asegurando que mantuvieran un contacto firme y constante con la superficie. Esta estabilidad es crucial para maximizar la tracción, lo que a su vez mejora la capacidad del robot para moverse sobre diferentes tipos de terreno sin perder el control.

FASE 3: Montaje del sensor ultrasónico
El siguiente paso fue el montaje del sensor ultrasónico, un componente crítico para la detección de obstáculos y la navegación autónoma del robot. Decidimos colocar este sensor sobre el motor mediano, aprovechando el espacio disponible y manteniendo el centro de gravedad bajo para evitar posibles vuelcos. El sensor ultrasónico se asegura con piezas adicionales, cuidadosamente seleccionadas para garantizar su estabilidad y evitar cualquier vibración que pudiera comprometer la precisión de la detección. Este sensor está diseñado para medir la distancia entre el robot y los objetos en su camino, lo que permite al robot ajustar su ruta en tiempo real. La precisión del sensor es vital, ya que cualquier error en la medición podría resultar en colisiones o desviaciones del camino programado.

FASE 4: Instalación del motor mediano
Una vez instalado el sensor ultrasónico, pasamos a la colocación del motor mediano, el cual es responsable de la maniobrabilidad lateral del robot. Este motor fue estratégicamente posicionado para controlar el mecanismo direccional, lo que permite al robot girar tanto hacia la izquierda como hacia la derecha de manera precisa y controlada. Para lograr esto, implementamos un sistema compuesto por una tuerca y varias piezas diseñadas para reforzar la estabilidad del sistema direccional. El motor mediano está configurado para responder rápidamente a las señales del cerebro del robot, lo que permite realizar giros suaves y evitar obstáculos de manera efectiva. La estabilidad y el soporte de las llantas también fueron reforzados en esta fase, utilizando componentes adicionales que aseguran que el robot mantenga su trayectoria incluso durante giros cerrados o cambios abruptos de dirección.

FASE 5: Colocación del cerebro del robot
La fase final del montaje involucra la integración del cerebro del robot, que es esencialmente el procesador central que coordina todas las acciones y respuestas del robot. Este componente es crucial, ya que gestiona las señales provenientes de los sensores y los motores, tomando decisiones en tiempo real basadas en la programación preestablecida. Para asegurar una integración sólida y funcional del cerebro con el resto del sistema, construimos una estructura de soporte utilizando piezas rectangulares. Esta estructura no solo soporta el peso del cerebro del robot, sino que también proporciona puntos de montaje seguros para los sensores de color, que son fundamentales para la navegación y la detección de señales en la pista. Cada pieza fue seleccionada y colocada con precisión, garantizando que el cerebro del robot esté protegido de vibraciones y choques, mientras que los sensores están posicionados de manera óptima para captar información del entorno con la máxima eficiencia.

- Primera fase de armado
![Primer-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Primer-Armado.jpg)

- Segunda fase de armado
![Segundo-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Segundo-Armado.jpg)

- Tercera fase de armado
![Tercer-Armado](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/Tercer-Armado.jpg)

- Base del ultrasonico
![18](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/18.jpg)

- Finalizando Armado
- ![17](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/17.jpg)

- Rescontrucción en pista
![20](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/20.jpg)

# Gestion de energia y los sentidos

CONEXION A	

Motor Grande: Este componente esencial facilita el movimiento de las llantas traseras del robot, proporcionando la potencia y precisión necesarias para maniobrar con eficiencia en diversas superficies y condiciones.

CONEXION B	

Motor Mediano: Este motor permite que el robot gire y cambie de dirección, facilitando movimientos precisos hacia la izquierda y la derecha, y contribuyendo a una mayor maniobrabilidad y control en su desplazamiento.

CONEXION 4	

Sensor Ultrasónico: Este sensor permite al robot detectar objetos a diferentes distancias y utiliza esta información para determinar el momento adecuado para determinar los cambios de dirección, garantizando así la seguridad y la precisión en sus movimientos.

CONEXION 3 Y 2 

Sensor de Color: Este sensor permite detectar los colores de los cubos en color rojo y verde de la pista perimitiendo que el robot decida hacia que lado debe girar 

# Controlador/Robot

Procesador: ARM9, 300 MHz.

Memoria RAM: 64 MB.

Almacenamiento: 16 MB de memoria flash y ranura para tarjeta microSD de hasta 32 GB.

Sistema Operativo:  Kendel Linux.

Voltaje de Funcionamiento: 6-9V DC.

Batería Recargable: Batería de ion de litio EV3 (10V).

Duración de la Batería: Aproximadamente 6 horas con uso continuo de la batería recargable.

# Sensores y margenes de error

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

![Superior](https://github.com/user-attachments/assets/ba01ced1-ba8d-419f-a658-8bd198c86b1a)

- Frontal
![Frontal](https://github.com/user-attachments/assets/40b66195-dde3-4b4f-bd2e-97b16724fb83)

- Posterior
![Posterior](https://github.com/user-attachments/assets/7a073041-7c3c-4fac-b9ff-d764988b38a7)

- Derecha
![Derecha](https://github.com/user-attachments/assets/82fa34ef-9c62-43d8-860b-4b9fb4966331)

- Izquierda
![Izquierda](https://github.com/user-attachments/assets/abb3d34d-5622-4e7a-a650-40928f0a642a)

- Inferior
![Inferior](https://github.com/user-attachments/assets/5c1bc11b-1f79-4cad-a5e4-de001e441e4b)

- Pruebas de Programacion
![21](https://github.com/ROBOTICAIPTC/New_Line/blob/main/v-photos/21.jpg)

- Pruebas en simulador de aerodinamica
![22](https://github.com/ROBOTICAIPTC/New_Line/blob/main/t-photos/22.jpg)


* `video` contiene el archivo video.md con el enlace a un video donde existe una demostración de manejo

# Ronda de desafio abierto
https://youtu.be/KI8TZq1QNDs

* `schemes` contiene uno o varios diagramas esquemáticos en formato JPEG, PNG o PDF de los componentes electromecánicos que ilustran todos los elementos (componentes electrónicos y motores) utilizados en el vehículo y cómo se conectan entre sí.

# Recomendaciones y tips                                                                                                                                                                                     

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



* `src` contiene código de software de control para todos los componentes que fueron programados para participar en la competencia

 # Version del progama

Lego Mindstorms EV3

v.1.5.3

https://education.lego.com/en-us/downloads/mindstorms-ev3/software/

* `models` es para los archivos de modelos utilizados por impresoras 3D, máquinas de corte por láser y máquinas CNC para producir los elementos del vehículo. Si no hay nada que agregar a esta ubicación, se puede eliminar el directorio.


* `other` es para otros archivos que pueden usarse para entender cómo preparar el vehículo para la competencia. Puede incluir documentación sobre cómo conectarse a un SBC/SBM y cargar archivos allí, conjuntos de datos, especificaciones de hardware, descripciones de protocolos de comunicación, etc. Si no hay nada que agregar a esta ubicación, se puede eliminar el directorio.
