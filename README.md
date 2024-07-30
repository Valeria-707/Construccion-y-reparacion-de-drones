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
  - Ala alta: Ubicada en la parte superior del dron.
  - Ala media: Ubicada en la parte media del fuselaje, da equilibrio y maniobrabilidad.
  - Ala bajo: Ubicada en la parte inferior del fuselaje.

- Ala giratoria
  - Usan las alas o los rotores giran a grann velocidad para elevar el dron.
  - Helicópteros son ejemplo.
 
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

Las hélices producen el empuje necesario para que el dron vuele. Siempre se deben elegir las hélices más grandes posibles en función del tamaño del marco y los motores para maximizar el empuje. A menor número de revoluciones (KV), mayor tamaño de la hélice.

Las hélices están fabricadas con diversos materiales, cada uno adecuado para usos específicos debido a sus características:

 - Plástico:
   - Muy comunes
   - Bajo costo
   - Flexibles
   - No resistentes para cargas pesadas

- Plástico Reforzado:
   -  Flexibles
   - Fuertes
   - Costo moderado
   - Rígidas

- Fibra de Carbono:

   - Rígidas
   - Fuertes
   - Ligeras
   - Aerodinámicas
   - Costosas
     
- Madera:
   - Costosa
   - Pesada
   - Ofrecen mayor impulso para cargas pesadas
     
El tamaño de una hélice se indica en pulgadas mediante cuatro dígitos. Los primeros dos dígitos indican el diámetro de punta a punta, y los otros dos dígitos indican el paso de la hélice, es decir, la distancia que avanza en un giro.

En términos de eficiencia, es mejor utilizar palas, pero se usan tres palas cuando el diámetro es muy pequeño y se necesita aumentar el empuje. Esto es común en aviones de ala fija y cuadricópteros.

### Fuselaje

El fuselaje es el cuerpo de un avión fabricado con diversos materiales para drones de ala fija:
 - Dron de espuma: Uso recreativo
 - Dron de madera: Uso recreativo
 - Dron de fibra de carbono: Uso profesional
 - Dron de fibra de vidrio: Uso profesional

### Carga útil

La carga útil incluye el piloto automático, la batería, el receptor del radio control, el módulo aéreo de telemetría y la cámara. Es el peso total de los componentes que se usarán en la construcción.

 - Se debe verificar que el fuselaje tenga espacio suficiente para albergar los componentes.

### Centro de gravedad

El centro de gravedad es el punto de equilibrio del dron. Si este punto está desubicado, el vuelo del dron puede volverse inestable o provocar su desplome.

### Servomotores

Son pequeños motores, hechos de metal o plástico, con un control preciso de posicionamiento. Se utilizan para tareas como inclinar una cámara hacia arriba o abajo.

### Marco multirrotor

Los marcos multirrotor tienen la ventaja de una simplicidad mecánica. La placa central del marco puede fabricarse en madera o termoplásticos utilizando impresoras 3D o máquinas CNC.

### Placa Central

Construida con fibra de vidrio o fibra de carbono. No debe exceder el peso máximo de despegue.

### Brazos

Fabricados con varios materiales como plástico, fibra de vidrio o fibra de carbono. Tienen formas de prismas rectangulares o tubulares; algunos pueden ser plegables.

###  PLaca de Districución de Energía

La Placa de Distribución de Energía (PDB) facilita la conexión de los motores con sus respectivos ESC y otros componentes. Esta placa ya viene integrada para simplificar la energización de los dispositivos electrónicos y motores.

 - Se debe verificar que su capacidad de corriente sea superiorm al consumo de los motores.

### Tren de aterrizaje

Si se requiere instalar un cardán (mecanismo de estabilización), también se debe instalar un tren de aterrizaje con una distancia suficiente entre la base del marco y el suelo.
 - Recubrir el tren de aterrizaje con tubos de espuma para proteger aún más la estabilización durante los aterrizajes.

### Monocasco

Es un marco ligero y robuso donde se encuentran los elementos que controlan el dron.
 - Los dornas que se compran listos para volar yaincluyen el monocasco.
 - A veces, los monocascos pueden ser incómodos al momento de repararlos

### Baterías


Se utilizan baterías de polímero de litio, también conocidas como LiPo. Estas baterías están compuestas por celdas con un voltaje mínimo de 3.7 volts y un máximo de 4.2 volts. Si la batería excede este rango, los químicos internos se alteran, lo que puede dañar la batería y, en casos extremos, provocar que explote.

*Capacidad*

La capacidad se mide en miliamperios hora (mAh) y aparece en la etiqueta. Cuanta mayor capacidad tenga, más tiempo podrá volar el dron.

*Desventajas*

A mayor capacidad, mayor será el peso de la batería.

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
 - Sirve para comprobar que la batería nos proporcionará la corriente suficiente.

### Controladores Electrónicos de Velocidad

Los Controladores Electrónicos de Velocidad (ESC) interconectan la batería y el controlador de vuelo para ajustar la velocidad de los motores.

*Caraterísticas*

 - Amperaje de salida: Define el tamaño del motor que se puede controlar
   Ejemplos:
    - 10 - 12 amperios: Multirrotores peueños
    - 20 - 30 amperios: Multirrotores con cámaras

 - Voltaje de Operación: Indica los voltajes mínimo y máximo con los que puede funcionar.

### Circuito Eliminador de Baterías

Los Circuitos Eliminadores de Baterías (BEC) reducen el voltaje de la batería a un nivel estable de 5 volts. Normalmente vienen incluidos en los ESC, pero hay excepciones.

*Tipos*
 - Switching BEC (SBEC)
    - No se calientan
    - Más eficientes
    - Pueden interfierir con los equipos de radio control

 - OPTO ESC
    - Controlador con aislante térmico
    - Evita la interferencia

 - BEC externo
    - Pueden insatalarse por separado
    - Pueden ser sustituidos por el módulo de potencia en algunos pilotos automáticos
  
### Cámaras y Cardanes

*Cámaras*
 - Cámaras FPV
    - Se instalan sobre el fuselaje
    - No necesitan cardán
    - Baja calidad
    - Transmisión en tiempo real
  
 - Cámara de Acción
    - Alta calidad
    - Almacenamiento en SD
    - Transmisión directa
    - Necesita cardán
    
  - Cámara profesional
     -  Alta calidad
     -  Usadas principlamente para cartografías y modelos de elevación
     -  Interfaz de control de disparo remoto
     -  Necesita cardán

*Cardán*

Estabiliza la cámara mientras el dron vuela, clasificándose según la cantidad de ejes
 - 2 ejes (cabeceo y alabeo)
    - Ideal para cámaras de acción
      
 - 3 ejes (cabeceo, alabeo y guiñada)
    -  Más robusto
    -  Costoso
    -  Ideal para la cinematografía y captura de imágenes

*Verificar que los motores soporten el peso de la cámara*

### Vista en Primera Persona

La Vista en Primera Persona (FPV) permite a las personas colocarse virtualmente en el asiento del piloto, gracias a una pantalla que muestra la vista del dron.

Se usa prinicpalmente:

- Actividades Profesionales:
   - Ofece imágenes y videos específicos
   - Usado en la cinematografía y cartografía

- Actividades Recreativas:
   - Trasnmite video a alta velocidad
   - Baja latencia
   - Usado en carreras de drones
   - Con cámaras tridimensionales

*Elección de la cámara*
 - Buena nitidez
 - Buen peso
 - Buena latencia:
    - Cámara FPV: 40-100 ms
    - Cámara de acción: 140 ms
    - Cámara profesional: 100 ms

*Antena*

Es el elemento más importannte del FPV, ya que permite la comunicación entre el dron y su controlador. La elección adecuada de la antena adecuada puede mejorar significativamente el rendimiento y la confiabilidad del dron. 

 - Polarización Lineal
   - Es el estándar
   - Los planos de la señal del recpetor y del transmisor están alineados
   - Mejor señal cuando el transmisor y el recpector estén en la misma posición
     
 - Polarización Circular
    - Los planos se combinan para hacer una señal cilíndrica
    - Aumenta la recepción
    - Diisminuye la instensida
    - Más robusta

## Lección 2

### Diseño de un dron

El diseño de un dron comienza con la definición de su aplicación. Los componentes varían según la aplicación específica.

 1. Una vez estimado el peso de la carga útil, se puede iniciar con la selección de motores, hélices y controladores electrónicos de velocidad (ESC).
 2. Con el peso estimado del dron, se debe revisar la tabla de datos de empuje de los motores para encontrar una combinación adecuada de motores y hélices.
 - La combinación debe producir un empuje al 50% de aceleración.
 - La elección del ESC está vinculada al consumo máximo de corriente del motor.
 - Si se desea que el dron vuele el mayor tiempo posible, se elegirá la batería con mayor capacidad.
 - A mayor capacidad de la batería, mayor será su peso.

 *Consumo máximo de una batería*
 Capacidad de la bateríia (Ah) X Tasa de descarga de la batería (C)

 *Tiempo de vuelo*
 Potencia total de la batería / Consumo de potencia del motor X 60 min

 *Potencia total de la batería*
 Voltaje X Ampers

 *Consumo de potencia del motor
Peso del dron (kg) / eficiencia 50%

###  Conexión de motores y ESC con soldadura elécctrica

La conexión de motores y ESC generalmente se realiza con conectores tipo "banana", pero también se pueden soldar.

1. Recortar los alambres y pelarlos con un pelacables.
2. Colocar thermofit en cada uno de los alambres del motor.
3. Conectar el cautín.
4. Sujetar los alambres con pinzas para tener las manos libres.
5. Acercar el cautín al alambre con la soldadura permitiendo que se rome una gota.
6. Repetir el paso anterior con cada uno de los alambres, verificando que sea logre el giro de motores deseados.
7. Unir los alambres con soldadura con ayuda del cautín.
8. Recorrer el thermofit hasta las uniones y acercar la punta del cautín caliente para que se encoja.
9. Repetir el proceso con cada conexión.

### Construcción del marco y acoplamiento de los motores con los ESC

Antes de construir un dron, debemos saber su aplicación. El tamaño del marco incluye un número que indica su diámetro.

Ejemplo:
ABC200 - 200 mm es el díametro

El tamaño del marco limita a los otros componentes

*Construcción*
1. Verificar que estén todos los componentes.
2. Construir el marco según su manual.
3. Medir la longitud de los brazos del dron.
4. Recortar los alambres de los motores y de los ESc de forma que descansen sobre los brazos.
5. Verificar el giro deseado en cada motor.
  -Habrá la misma cantidad de motores girando en sentirdo horiario y antihorario
6. Soldar los motores y los ESC
7. Verificar la orientación de los motores según el controlador de vuelo.
8. Voltear el marco y enroscar los tornillos en la parte inferior a través del brazo hasta el motor.
9. Asegurar los ESC con bridas de plástico.
10. Soldar los cables de alimentación de los ESC.
11. Cubrir con cinta de aislar.

### Conexión de dispositivos de control, piloto automático y batería

1. Colocar la electrónica de vuelo
2. Verificar que los controladores de velocidad cuenten con un circuito BEC
    -Si no es el caso, deberás intalar un circuito BEC entre la PDB y el controlador de vuelo.
3. Colocar el piloto automático sobre el marco con la flecha apuntando al frente del dron, no sin antes colocar una placa antivibraciones y pregarla con cinta de espuma de doble cara.
4. Conectar o soldar los cables del controlador de velocidad al pilóto automático o contorlador de vuelo según lo indicado por el fabricante
 -Si el controlador cuenta con un eliminador de tipo conmutador, solo conecta uno de los cables rojos al pilóto automático o controlador de vuelo.
5. Conectar el receptor del radiocontrol verificando el tipo de codificación de la señal.
6. Conectar el receptor y el piloto auotmático según sus instrucciones.
7. Colocar el recpetor en su sitio sobre el marco y *asrgurar que la antena no quede atrapada por el giro de las hélices*.
8. Conectar la batería a la PDB, sujetándola al marco con cinta o correas de gancho.
9. Conectar el módulo GPS revisando el manual.
10. Instalar el GPS, montando el módulo en un mástil, poniendo el mástil arriba del dron asegurando que el módulo está apuntando enfrente del dron.

### Ensamblado del cardán, cámara y FPV

*Cardán*
1. Atornillar el soporte antiviración en la parte inferior.
2. Colocar la cámara en el cardán.
3. Instalar el cardán en el soporte.
4. Conetar los cables de alimentación a la batería, esperando que emita un pitido o prenda algún led.
5. Desconectar los cables.

*Conexión del transmisor FPV*
1. Conectar el FPV a la cámara.
2. Conectar los cables de alimentación del transmisor a la PDB.
3. Instalar (de no tener FPV) un viltro de voltaje entre el FPV y la PDB.
4. Conectar la cámara al transmisor de video.
5. Fijar la cámara FPV y transmisor al frente del dron con cinta adhesiva doble cara o bridas de plástico.
6. Colocar la antena al transmisor de video.
7. Conectar los cables de alimentación del transmisor al cable de equilibrio de la batería.
8. Esperamos que la cámara encienda y dectonectamos los cable de alimentación.

### Configuración del piloto automático

1. Descargar el software del configurador de vuelo
2. Conectar el micro USB al puertto del controlador de vuelo (CV), luego el USB al puerto correspondiente. *No hacer de otro orden o se dañará el componente*
3. Con el configurador abierto, dar click en "Conectar"

*Actualización del Firmware*
1. Oprimir en "Desconectar".
2. Elegir la opción "Instalar Firmware", lueo el modelo del controlador de vuelo y l última versión del firmware.
3. Elegir "Cargar Firmware".
4. Observar el botón "Instalar Firmware" debiendo este cambiar de color.
5. Algunos controladores de vuelo requieren el modo "bootloader" por lo que deberémos hacer un corto con algún objeto conductor.
6. Presionar le botón "Instalar Firmware".
7. Desconectar el corto.

*Calibración del acelerómetro*
1. Oprimir "Conectar" en el interfaz.
2. Elegir la pestaña "Setup" o "Configurar".
3. Colocar el dron en una supericie nivelada.
4. Dar clic en "Calibrate Accelerometer".

*Ajustes de radiocontrol*
1. Dar clic en "Reciver" o "recpetor" en la interfaz.
2. Buscar el modelo del radiocontrol en el apartado "Channel Map", luego precionar en "Guardar" o "Save".
3. Mover las palancas para comprobar que las barras de estado reaccionen correctamente.

*Configuración de los modos de vuelo*
1. Dar clic en "Receptor" en la intterfaz.
2. Verificar cada interruptor.
3. Dar clic en "Modos".
4. Activar la casillas "HIGH".
5. Activar "LOW, MED y HIGH".
6. Dar clic en la casilla "Add Range".
7. Elegir el canal y el rango.



   
## Lección 3

### Equilibrio de las hélices

Las hélices son suseptibles a deformarse provocando turbulencias o colapsando contra el suelo, un árbol o cualquier otro objeto.

*¿Cómo equilibrarlas?*

1. Colocar la hélice en el balanceador para identificar la ala más pesada.
2. Cortar un trozo de cinta de aislar y pergarlo en la pala más ligera.
    - Si la hélice se inclimna en la pala donde olocamos la cinta significa que es demasiado pesado. Sin embargo, solo se cobrará más cerca del centro hasta nivelarla.
3. Una vez equilibradas las palas de la hélice balanceamos el cubo.
   3.1 Colocar la hélice a 45° del balanceador, soltamos y observar si se inclina a algún lado.
   3.2 Voltear la hélice y repetir el paso anterior hasta que identifiquemos el lado pesado del cubo.
   3.3 Intentar con varios ángulos de inclinación.
4. Añadir cinta de aislar al lado más ligero.
   - O rebajar el lado más pesado con una lija de agua o lima.
5. Cuando la hélice está equilibrada, permanecerá estable. No importa el ángulo de inclinación.

*Evitar usar hélices de color blanco ya que serán difíciles de ver si la hélice está en mal estado.*

### Prueba de cortocircuito

Es crucial evitar cortocircuitos, especialmente en las almohadillas de la PCB (Placa de Distribución de Energía) del motor y el controlador.

¿Cómo saber si hay algún cortocircuito?

Utilizaremos un multímetro en la opción de continuidad:

 - Todas las almohadillas positivas están conectadas entre sí, por lo que al tocar cualquiera de ellas se escuchará un "beep".
 - Lo mismo ocurrirá con las almohadillas negativas.
 - Al tocar una almohadilla positiva y una negativa, no se debe escuchar ningún sonido.
 - Si el multímetro suena, deberemos encontrar el corto.
 - El cortocircuito puede deberse a un poco de soldadura derretida en una almohadilla positiva y negativa.

*Realizar este procedimiento siempre antes de ensamblar*

### Enlace receptor-transmisor de radio control

El proceso de enlace entre el transmisor y el receptor es similar al proceso de emparejamiento entre un dispositivo vía inalámbrica.

*¿Cómo conectar?*

1. Conectar los pines PPM del receptor en los pines del dispositivo transmisor-receptor asíncrono o UART del controlador de vuelo usando cables tipo Dupont:
   - Primero conectar los cables de señal (S)
   - Luego los cables de alimentación (V)
   - Al final, los cables de tierra (GND)
   
   *Hacerlo en ese orden para no quemar la placa del controlador*

2. Abrir el software del controlador de vuelo en tu PC y conectar la placa de tu controlador:
   - Primero conectar la conexión micro USB, y luego la conexión USB.

3. Energizar el controlador de vuelo con 5V, puede ser obtenido de un controlador de velocidad conectado a la batería lipo.

4. Da clic en "conectar" y luego en "configuración de interfaz". En la sección "modo del receptor", elegimos el protocolo de enlace "PPM", para dar clic en "guardar y reiniciar".

5. Damos clic en el menú de configuración del transmisor, seleccionamos "output mode", desconectamos la alimentación del controlador de vuelo, elegimos PPM y volvemos a conectar la alimentación al controlador.

6. Vamos a la interfaz, damos clic en conectar, elegimos la pestaña de receptor. Ahora aparece el mapeo de los canales, comprobamos que la respuesta de las barras de estado coincida con el movimiento de las palancas y ajustamos las rangos de respuesta.

*Protocolo de enlace serial*

1. Conectar los pines PPM del receptor en los pines del dispositivo transmisor-receptor asíncrono o UART del controlador de vuelo usando cables tipo Dupont:
   - Primero, conectar los cables de señal (S).
   - Después, conectar los cables de alimentación (+).
   - Al final, conectar los cables de tierra (GND).
   
   *Hacerlo en ese orden para no quemar la placa del controlador*

2. Abrir el software del controlador de vuelo en tu PC y conectar la placa de tu controlador:
   - Primero la conexión micro USB y luego la conexión USB.

3. Energizar el controlador de vuelo con 5V, que puede ser obtenido de un controlador de velocidad conectado a la batería lipo.

4. Dar clic en "conectar", ir a la pestaña de puertos y activar el interruptor RX del puerto que hayas escogido. Dar clic en "guardar y reiniciar".

5. Ir a la pestaña de configuración. En la sección "modo del receptor", elegir el protocolo de enlace serial. En la sección "proveedor del receptor serial", elegir el protocolo de comunicación entre el receptor y el controlador de vuelo, y dar clic en "guardar y reiniciar".

6. En el menú de configuración del transmisor, seleccionar "output mode". Ir a la alimentación del controlador de vuelo, elegir el protocolo serial y volver a conectar la alimentación al controlador.

7. Dar clic en "conectar" en la interfaz, elegir la pestaña del receptor y comprobar que las barras de estado coincidan con el movimiento de las palancas.

 *Es posible no tener que ajustar los controles*

*Enlace rápido*

 1. Presionar el botón de reinicio y conectar el receptor con cables Dupont.

 - Primero, conectar los cables de señal (S).
 - Luego, conectar los cables de alimentación (+).
 - Finalmente, conectar los cables de tierra (GND).

*Realizar las conexiones en ese orden para evitar daños en la placa del controlador.*

 2. Encender el transmisor y abrir "Model Setup". En la fila "Mode", elegir el protocolo de conexión entre el receptor y el controlador de vuelo (CV). En la fila "Receiver", seleccionar la opción "Bind". Los LEDs del receptor parpadearán, indicando que el enlace ha sido exitoso.

 3. Desconectar la alimentación del receptor y conectar los nuevos pines. Un LED verde debe encenderse y en la pantalla del transmisor debe aparecer el símbolo de una antena.

Si esto ocurre, el enlace ha sido exitoso.




## Lección 4

### Controles de seguridad antes de volar

 - Asegúrate de que la batería LiPo y la batería del transmisor de radiocontrol estén completamente cargados.
 - Verfica si está autorizado volar en el lugar seleccionado.
 - Consultar el pronóstico del tiempo para evaluar las condiciones del viento.
 - Asegura correctamente todo el equipo, especialmente la batería.
 - Comprueba que los cables estén firmemente asegurados.
 - Ajusta los tornillos.
 - Comprueba que los cables estén firmemente asegurados.
 - Corrobora el interfaz del piloto automático.

### Segurdad durante el vuelo

Cada país cuenta con su propio código civil aeronáutico. Debes revisarlo, atender sus indicaciones y evitar volar de forma que no ponga en peligro a nadie.

  - Mantén la vista en tu dron para ver y evitar obstáculos.
  - Evita que la distancia horizontal de vuelo exceda los 457 metros (1,500 pies).
  - Evita volar a una altura mayor a 120 metros (400 pies).
  - Respeta las instrucciones de operación del fabricante en cada vuelo.
  - Mantén una distancia vertical de al menos 46 metros (150 pies) de personas y propiedades.
  - No sobrevueles multitudes ni áreas urbanas, manteniendo una distancia de al menos 150 metros (500 pies).



### Drones anfibios y submarinos

#### Drones submarinos

Se utilizan principalmente en actividades industriales y militares, como la pesca, filmaciones submarinas, inspección de cascos de embarcaciones, presas, puertos, infraestructuras submarinas e investigación científica; pero también hay modelos para aficionados.

La mayoría está equipada con sensores para evitar colisiones con obstáculos, cámara HD/1080p o UHD/4k, y focos potentes.

#### Drones alámbricos

Cuentan con un cable para transmitir video e impedir que el dron se hunda o sea arrastrado por alguna corriente.

- Cámara 4k
- Focos de 1000 hasta 4000 lúmenes
- Gafas FPV
- Brazos robóticos para tomar muestras
- Lastres para sumergirse
- Baterías de 60 - 280 min
- Máximo alcance de inmersión de 30 - 300 m

### Drones inámbricos

- Uso recreativo.
- Alcanzan 60 m de profundidad.
- Tiempo de vida de la batería de 60 - 120 min.
- Función de seguimiento.
- Útil en buceo.
- Retorno automático antes de que la batería se agote.

### Drones anfibios

- Vuelan y flotan.
- Se sumergen ligeramente.
- Cámara FPV y de acción.
- Características de un dron aéreo.
