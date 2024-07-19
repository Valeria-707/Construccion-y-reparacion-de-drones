# Construcción y reparación de drones

## Lección 1

### ¿Qué es?

Son sistemas de aeronaves pilotadas a distancia no tripulaladas (RPAS) que gracias a su tamaño y versatilidad son de mucha ayuda.
Estos son empleados por:

- Ejércitos
- Empresas
- Organizaciones
- Aficinados
  - Profesionales
  - Recreativos
  - Educativos.


### Tipos

- Ala fija
  - Ala alta: Ubicada en la parte superior del dron
  - Ala media: Ubicada en la parte media del fuselaje, da equilibrio y maniobrabilidad
  - Ala bajo: Ubicada en la parte inferior del fuselaje

- Ala giratoria
  - Usan las alas o los rotores giran a grann velocidad para elevar el dron
  - Helicópteros son ejemplo
 
### Campos de Trabajos

1.- Elaborar mapas
   - Con el uso de cámaras especiales y georreferenciados GPS, es posible ubicar con gran precisión las coordenadas sobre el suelo.

2.- En la industria agrícola
   - En la actualidad, las aeronaves están equipadas con sensores de luz visible (RGB) y de infrarrojo cercano (NDVI), permitiendo así analizar la salud de los cultivos.

3.- En la construcción minera
   - Se emplean para mapear tridimensionalmente la topografía del terreno y detectar artículos en áreas de difícil acceso.

4.- Fotografía
   - Videos con mayor calidad y resolución.
   -  Usado para supervisar el medio ambiente y labores de atención de emergencias.

5.- Mecánica
  - Diseña y construye.
  - Conocer los planos.

6.- Electrónica
  - Diseña y construye.
  - Interconectar las placas y componentes.

7.- Elaboración de prototipos
  - Consiste en pruebas para tener una visión de las ideas planeadas.
  - Elaboración de bocetos y desarrollo de los primeros prototipos.


### Tamaño

Dependiendo de la masa total del dron, estos deben seguir las regulaciones pertinentes y vigentes del país donde vuelen.

- Peso máximo:
  - 2 kg o menos
  - 2 kg hasta 25 kg
  - 25 kg o más

- Categoría:
  - 2 kg o menos: RPAS Micro
  - 2 kg hasta 25 kg: RPAS Pequeño
  - 25 kg o más: RPAS Grande

- Uso:
  - 2 kg o menos: Privado recreativo
  - 2 kg hasta 25 kg: Privado no comercial
  - 25 kg o más: Comercial


### Caja de Herramientas, Materiales y Equipo de Protección

**Herramientas**
 - Destornillador plano
 - Destornillador de estrella
 - Destornillador de punta
 - Multímetro
 - Llaves tipo Allen
 - Tornillo de banco
 - Pinzas o alzadores de plástico
 - Bridas o cintas de velcro
 - Empaladora o pinzas de compresión

**Materiales**

 - Cables eléctricos AWG (diferentes colores)
 - Cinta para aislar
 - Fijador de roscas
 - Cables Dupont (hembra-macho)
 - Soldadura
 
**Equipo de Protección:**
 - Pulsera antiestática
 - Gafas protectoras
 - Guantes antiestáticos



## Lección 2

### Piloto Automático

Procesa la información de los sensores, activa los motores y otros dispositivos de control considerandose como el cerebro del drom. Se deberá colocar el piloto automático en un soporte antivibración para eviat la desconfiguración de sus sensores. 

*Se compone de:*
 - Controlador de vuelo
 - Sensores
 - Receptores satelitales externos
 - Radiocomunicaciones (módulo de telemetría)
    - Le da funciones al dron

Las funciones se pueden modificar desde un celular, computadora o tableta. Los controladores de vuelo más básicos se usan en helicópteros de carrera. Solo cuentan con los sensores esenciales (acelerómetro y giroscopio). Hay algunos que cuentan con una pantalla LCD con botones para configurarlo sin necesidad de conectarlo a una PCB. Las controladoras más avanzadas incluyen sensores más complejos como barómetros, GPS y otros accesorios.

**Sensores**

 - Acelerómetros y giroscopios
   - Compuestos por 3 acelerómetros para medir la gravedad en los ejes x, y, z.

 - Barómetro
   - Sensor que mide la presión atmosférica para determinar la altitud de vuelo.

 - Magnetómetro
   - Sensor de brújula que mide el campo magnético para conocer la dirección del dron (normalmente integrado en el GPS).

 - GPS
   - Mide el tiempo que tardan las señales en llegar al receptor para determinar su posición tridimensional con respecto a la tierra. Su precisión es de 5-10 metros horizontalmente y 15 metros verticalmente.

 - Módulo de alimentación
   - Recibe la tensión de la batería, la filtra y la regula para proporcionar 3.3 o 5V al controlador de vuelo. También mide la capacidad de energía restante.

 - Estación terrestre
   - Módulo de telemetría instalado en un dispositivo electrónico con software de control terrestre. Tiene un alcance de 1 km.


### Sistema de radiocontrol

Está conformado por un transmisor, así como un receptor montado arriba del dron que está conectado al piloto automático. El transmisor convierte el movimiento de las palancas y los botones en señales al receptor.

  - Alabeo: Eje longitudinal
  - Cabeceo: Eje transversal
  - Guiñada: Eje vertical

*Hay dos modos de para configurar el transmisor:*

Modo 1
  - El acelerador y el alabeo se encuentran en la palanca derecha. Hacia arriba acelera y hacia abajo aminora la marcha. Los movimientos de izquierda y derecha inclinan el avión. Esta palanca no tiene muelle (no regresa al centro).
  - La palanca izquierda controla el cabeceo y la guiñada. Arriba asciende, abajo desciende, derecha e izquierda giran. Tiene un muelle (regresa al centro).

Modo 2
  - El acelerador y la guiñada se encuentran en la palanca izquierda. Hacia arriba acelera, abajo aminora la marcha, derecha e izquierda giran. No tiene muelle.
  - En la palanca derecha se controla el alabeo y el cabeceo. Arriba eleva, abajo desciende, derecha e izquierda inclinan el avión. Tiene un muelle.


**Los Canales de Radio**

Los canales son señales de radio que controlan cada función del avión.

*Se necesitan mínimo 5 canales*
   - CH1: Acelerador
   - CH2: Alabeo
   - CH3: Guiñada
   - CH4: Cabeceo
   - CH5: Modos de vuelo

Aunque se pueden usar más canales, se debe revisar el manual de usuario para buscar las funciones que necesitamos.

*Los Receptores*
Cuentan con un número específico de canales para las funciones que se requieran, como de 16 canales. Al conectar el receptor con el transmisor se le llama enlace y difiere según el modelo de RC. Antes de comprar un receptor RC se debe considerar el tipo de antena. Después de esto, considerar la solidez y el rango de la conexión. Deben instalarse lejos de la electrónica y en un costado para que funcionen dentro de la banda de frecuencia de 2.4 GHz.

   - Una antena: Mala recepción si se usa por mucho tiempo.
   - Una antena de diversidad: Incrementa la capacidad de captación de la señal.
   - Antenas impresas o de PCB: Tienen mejor recepción a grandes rangos.

### Motores y Hélices

**Motores**
Los drones usan motores eléctricos sin escobillas del tipo "outrunner", es decir, sin carcasa externa. Estos motores se componen de dos partes principales:

*El estator:* La parte fija del motor, con bobinas dispuestas en un patrón radial.
*El rotor:* La parte giratoria con imanes permanentes en su interior.

El modelo de un motor se identifica con un par de números de 4 dígitos cada uno. En el primer número, los dos primeros caracteres indican el modelo del motor, los dos siguientes indican el diámetro, y los últimos dos caracteres señalan la altura del estator en milímetros.

Para el segundo número indica la constante de revoluciones por minuto.

Para escoger el motor adecuado para nuestro dron es necesario saber lo siguiente para escoger el más adecuado

*Diámetro:*

3"

4"

5"

6"

7"


*Tamaño del motor*

3": 1 306

4": 1 806

5": 2 204 - 2 206

6": 2 204 - 2 208

7": 2 206 - 2 210


*Rango KV*

3": 3 000-4 000

4": 2 600-2 800

5": 2 300-2 600

6": 1 900 - 2 300

7": 1 450 - 1 600



**Hélices**

Producen el empuje que el dron necesita para volar, simepre se eligen las hélices más grandes posibles de acorde al tamaño del marco y de los motores que utilice para maximizar el empuje.
Entre menos revoluciones (KV), más grande la hélice.

Las hélices están hechas de varios materiales, y cada uno es especial para cada uso por sus caraccterísticas.
 - Plástico:
    - Muy comunes
    - Bajo costo
    - Flexibles
    - No resistentes para carga

 - Plástico Reforzado:
    - Flexibles
    - Fuertes
    - Costo moderado
    - Rigidas
  
 - Fribra de carbono:
    - Rigidas
    - Fuertes
    - Ligeras
    - Aerodinámicas
    - Cosotas
  
 - Madera:
    - Costosa
    - Pesada
    - Con mayor impulso apara carga pesada

El tamaño de una hélice va indicada en pulgadas por cuatro digitos. Los primeros dos dígitos indican el díametro entre punta a punta, los otroa dos dígitos indican el paso de la hélices, es deir, la distancia ue avanza en un giro.

En términos de eficiencia es mejor usar palas, pero se usan 3 palas cuando el diámetro es muy pequeñi y tienen que aumentar el empuje. Son vistas principalmente eb avones de ala fija y cuadricópeteros.
