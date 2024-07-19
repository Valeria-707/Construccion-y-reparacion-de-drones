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

*Sensores*

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
