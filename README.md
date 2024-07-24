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

### Fuselaje

Es el cuerpo de un avión fabricado de diversos materiales para los drones de ala fija.
 - Dron de espuma: Uso recreativo
 - Dron de madera: Uso recreativo
 - Dron de fibra de carbono: Uso profesional
 - Dron de fibra de vidrio: Uso profesional

### Carga útil

El pilóto automático, la batería, el recpetor del rdio control, el módulo aérreo de telemetría y la cámara conforman la carga útil, siendo el peso de todos los componentes que se usarán en la construcción.

 - Se debe verificar que el fuselaje tenga espacio suficiente para albergar los componentes

### Centro de gravedad

Es el punto de equilibriodel deonn, si este punto está desubicado, el vuelo del dron puede ser inestable o provocar su desplome.

### Servomotores

Son pqueqños motores, hechhos de metol o plastico con un preciso control de posicionamiento. También se utilizan en tareas como inncinar una cámara hacia arriba o abajo.

### Marco multirrotor

Cuentan con la ventaja de su simplicidad mecánica, y la placa central de su marco puede fabricarse en madera i termipláticos en impresoras 3D o máquinas CNC.

### Placa Central

Construida con fibbra de vidrio o fibra de carbono. Esta no debe de exceder el peso máximo de despegue.

### Brazos

Fabricados de varios materiales como; plástico, fibra de vidrio o fibra de carbono. Tienen formas de prismas rectangulares o tubulares e incluso algunos pueden llegar a ser pegables.

###  PLaca de Districución de Energía

La Placa de Distribución de Energía o también conocido por sus siglas en inglés PDB (Power Distribution Board) evita la tedios tarea de soldar motores con sus respectivos ESC y el resto de componentes. Esta placa ya viene integrada para facilitar la energización de los dispositivos electrónicos y motores.
 - Se debe verificar que su capacidad de corriente sea superiorm al consumo de los motores.

### Tren de aterrizaje

Si se requiere instalar un cardán (mecanismo de estabilización) se debe de instalar igualmente un tren de aterrizaje, con una distancia sificiente entre la base del marco y el suelo.
 - Recubre el tren de aterrizaje con tubos de espuma para proteger aún más la estabilización durante los aterrizajes.

### Monocasco

Es un marco ligero y robuso donde se encuentrab los elementos que controlan el dron.
 - Los dornas que ya se adquieren listos para volar ya los incluyen desde su compra.
 - A veces pueden ser incómodos al momento de repararlos

### Baterías


Se utilizan baterías de polímero de litio, también conocidas como LiPo. Estas baterías están compuestas por celdas con un voltaje mínimo de 3.7 volts y un máximo de 4.2 volts. Si la batería excede este rango, los químicos internos se alteran, lo que puede dañar la batería y, en casos extremos, provocar que explote.

*Capacidad*

Su capacidad se mide en miliamperios hora (mAh) y aparece en la etiqueta. Cuanta mayor capacidad utilicemos, más tiempo podrá volar el dron.

*Desventajas*

Entre más capacidad ocupemos, mayor será el peso.

*Celdas - Tensión Normal - Tensión mínima - Tensión máxima*

1s -  3.7 volts - 3 volts - 4.2 volts

2s - 7.4 volts - 6 volts - 8.4 volts

3s - 11.1 volts - 9 volts - 12.6 volts

4s - 14.8 volts - 12 volts - 16.8 volts 

5s - 18.5 volts - 15 volts - 21 volts

6s - 22.2 volts - 18 volts - 25.2 volts

*Tasa de descarga o Clasificación (C)*

Indica que tan rápido se extrae la energía de la batería.
 - Se calcula multiplicando la capacidad de la batería por la tasa de descarga.
 - Sirve para comprobar ue la batería nos dará la corriente suficiente.

### Controladores Electrónicos de Velocidad

Los Controladores Electrónicos de Velocidad o ESC por sus siglas en inglés (Electronic Speed Controller) son disposistivos que interconectan a la batería y al controlador de vuelo para hacer girar a los motores a las velocidades deseadas.

*Caraterísticas*

 - Amperaje de salida: Define el tamaño del motor que se puede controlar, ejemplo:
    - 10 - 12 amperios: Multirrotores peueños
    - 20 - 30 amperios: Multirrotores con cámaras

 - Voltaje de operación: Indica los voltajes mínimo y máximo con los que puede funcionar.

### Circuito Eliminador de Baterías

Los Circuito Eliminador de Baterías o BEC por sus siglas en inglés (Battery Eliminator Circuit) reducen ele voltaje de la batería hasta un voltaje estable de 5 volts. Normalmente vienen incluidos en los ESC, pero hay excepciones.

*Tipos*
 - Switching Bec (SBEC)
    - No se calientan
    - Más eficientes
    - Interfiere con los equipos de rad.iocontrol

 - OPTO ESC
    - Controlador con aislante térmico
    - Evita la interferencia

 - BEC externo
    - Pueden insatalarse por separado
    - Pueden ser sustituidos con el módulo de potencia en algunos pilotos automáticos
  
### Cámaras y Cardanes

*Cámaras*
 - Cámaras FPV
    - Se instalan sobre el fuselaje
    - No necesitan cardán
    - Baja calidad
    - Transmisión en tiempo real
  
 - Cámara de acción
    - Alta calidad
    - Almacenamiento en SD
    - Transmisión de forma directa
    - Necesita cardán
    
  - Cámara profesional
     -  Alta calidad
     -  Usadas normalmente en cartografías y para modelos de elevación
     -  Interfaz de control de disparo remoto
     -  Necesita cardán

*Cardán*

Estabiliza la cámara mientras el dron vuela, clasificándose dependiendo de la cantidad de ejes
 - 2 ejes (cabeceo y alabeo)
    - Ideal para cámaras de acción
      
 - 3 ejes
    -  Más robusto
    -  Costoso
    -  Ideal para la cinematografía y captura de imágenes

*Verificar que los motores soportarán la cámara*

### Vista en Primera Persona

La Vista en Primera Persona, conocida por sus siglas en inglés FPV (First Person View), permite a las personas colocarse virtualmente en el asiento del piloto, gracias a una pantalla que muestra la vista del dron.

*Se usa prinicpalmente*

- Actividades profesionales
   - Da imággenes y videos específicos
   - Usado en la cinematografía y cartografía

- Actividades recreativas
   - Trasnmite video a gran velocidad
   - Con un bajo valor de latencia
   - Usado en carreras de drones
   - Con cámaras tridimensionales

*Elección de la cámara*
 - Buena nitidez
 - Buen peso
 - Buena latencia
    - Cámara FPV: 40-100 ms
    - Cámara de acción: 140 ms
    - Cámara profesional: 100 ms

### Cardán

El cardán es un componente que estabiliza la cámara mientra el dron está en movimiento

*Clasificación*
 - 2 Ejes
    - Alabeo y Cabeceo
    - Ideal para cámara de ación
      
 - 3 Ejes
    - Alabeo, Cabeceoy Guiñada
    - Más robusto y costoso
    - Ideal para la cinematografía y captura de imágenes

*Antena*

Es el elemento más importannte del FPV, ya que permiten la comunicación entre el dron y su controlador. La elección de la antena adecuada puede mejorar significativamente el rendimiento y la confiabilidad del dron. 

 - Polarización Lineal
   - Es el estándar
   - Los planos de la seal del recpetor y del transmisor estan alineados
   - Habrá mejor señal mientras  el transmisor y el recpector estén en la misma posición
     
 - Polarización Circular
    - Los planos se combinan para hacer una señal cilíndrica
    - Aumenta la recepción
    - Diisminuye la instensida
    - Más robusta

## Lección 2

### Configuración del piloto automático

1. Descargar el software del configurador de vuelo
2. Conectar el micro USB al puertto del controlador de vuelo (CV), luego el USB al puerto correspondiente. *No hacer de otro orden o se dañará el componente*
3. Con el configurador abierto, dar click en "Conectar"

*Actualización del Firmware*
1. Oprimir en "Desconectar"
2. Elegir la opción "Instalar Firmware", lueo el modelo del controlador de vuelo y l última versión del firmware.
3. Elegir "Cargar Firmware"
4. Observar el botón "Instalar Firmware" debiendo este cambiar de color
5. Algunos controladores de vuelo requieren el modo "bootloader" por lo que deberémos hacer un corto con algún objeto conductor
6. Presionar le botón "Instalar Firmware"
7. Desconectar el corto

*Calibración del acelerómetro*
1. Oprimir "Conectar" en el interfaz
2. Elegir lapestaña "Setup" o "Configurar"
3. Colocar el dron en una supericie nivelada
4. Dar clic en "Calibrate Accelerometer"

*Ajustes de radiocontrol*
1. Dar clic en "Reciver" o "recpetor" en la interfaz
2. Buscar el modelo del radiocontrol en el apartado "Channel Map", luego precionar en "Guadar" o "Save"
3. Mover las palancas para comprobar que las barras de estado reaccionen correctamente

*Configuración de los modos de vuelo*
1. Dar clilic en "Receptor" en la intterfaz
2. Verificar cada interruptor
3. Dar clic en "Modos"
4. Activar la casillas "HIGH"
5. Activar "LOW, MED y HIGH"
6. Dar clic en la casilla "Add Range"
7. 7. Elegir el canal y el rango
   
### Ensamblado del cardán, cámara y FPV

*Cardán*
1. Atornillar el soporte antiviración en la parte inferior
2. Colocar la cámara en el cardán
3. Instalar el cardán en el soporte
4. Conetar los cables de alimentación a la batería, esperando que emita un pitido o prenda algún led
5. Desconectar los cables

*Conexión del transmisor FPV*
1. Conectar el FPV a la cámara
2. Conectar los cables de alimentación del transmisor a la PDB
3. Instalar (de no tener FPV) un viltro de voltaje entre el FPV y la PDB
4. Conectar la cámara al transmisor de video
5. Fijar la cámara FPV y transmisor al frente del dron con cinta adhesiva doble cara o bridas de plástico
6. Colocar la antena al transmisor de video
7. Conectar los cables de alimentación del transmisor al cable de equilibrio de la batería
8. Esperamos que la cámara encienda y dectonectamos los cable de alimentacion

### Conexión de dispositivos de control, piloto automático y batería

1. Colocar la electrónica de vuelo
2. Verificar que los controladores de velovidad uentan con un circuito BEC
   -Si no es el caso, deberás intalar un circuito BEc entre ñla PDB y el controlador de vuelo
3. Colocar el pilóto automático sobre el marco con la flecha apuntando al frente del dron no sin antes colocar una placa antivibraciones y pregándolo con cinta de espuma de doble cara
4. 
