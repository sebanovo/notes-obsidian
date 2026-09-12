# Historia SIG
- Información antigua en punots, lienas y areás dibujados en papel
- Colores figuras, texturas.
- Consecuencias para la recolección y codificación:
  - Perdidad de datos mapas extraviados quemados, etc.
  - Consumo de tiempo para obtener un mapa de un lugar geografico
  - Dificultad en la recuperación
  - Combinación con otros datos espaciasles: La escala.

# Partes de un SIG
- DATOS (mapas)
- SIG (almacenamiento)
- INFORMACION (productos)

# Que es un SIG
Geografia <-> Geo - Tierra, Grafia - Diseño
- Geografia:  "La ciencia que estudia el diseño que sobre la tierra ha trazado el hombre" u otra definición de la palabra geografia es "escribir acerca de la tierra"
- Información Geografica: Es una abstracición o representacion de la realidad geografica o también conoocidao como paisaje.

- SIG: "Es una colección organizada de hardware, software y datos geográficos y personal asignado para la captura, almacenje, actualización, manipuleo, análisis y despliegue de todas las formas de Información referenciada geográficamente"

- UNION
- son la clave para el poder de SIG
- Visualización del analisis de los datos
- Ubicación Geografica

# Operaciones Espaciales
- Muchos programas de computación como ser Excel o paquete sde dibujo (auto CAD) pueden manejar datos simples geograficos o espaciales
- Pero un SIG  es solamente un SIG  si este permite operaciones espaciales sobre los datos


### A) Consultas no espaciales
- No require almacenar valores de lat y long
- No describe lugares de relacionan
- Ej: Cual es el número promedio de gente que trabaja con  SIG en una localización?
### B) Consultas espaciales
- Solamente son respondidas usando latitud y longitud 
- Solo un SIG puede responder estas consultas
- Ej. Cuante gente trabaja en SIG en la parte norte de la ciudad de Santa Cruz?

 ✅ **DATOS NO ESPACIALES (ATRIBUTOS)** : Describe la información acerca de las características geográficas

 ✅ **DATOS ESPACIALES (GEOMETRÍA)** : Describe la localización, la forma de las características geográficas, relación con otras características
# Preguntas que un SIG puede responder
1. Localización o Posición Geografica (What is at...?)
2. Condición  (Where is it...?)
3. Tendencia (What has changed since...?)
4. Patrones (What spatial patterns exist?)
5. Modelamiento (What if...?)

# TIPOS DE CONSULTAS

| Tipo                | Definición                                                                                                 | Ejemplo                                                                     |
| ------------------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| **a. MODELAMIENTO** | Busca **predecir o simular** escenarios futuros o hipotéticos usando modelos matemáticos o espaciales.     | "¿Cuál será la extensión de la inundación si el río crece 3 metros?"        |
| **b. TENDENCIA**    | Analiza **cambios a lo largo del tiempo** (evolución, crecimiento, desplazamiento).                        | "¿Cuál fue el curso del río Piraí en 1980?" ✅                               |
| **c. LOCALIZACIÓN** | Responde a **¿dónde está?** o **¿dónde ocurre?** algo en un momento actual o sin referencia temporal.      | "¿Dónde se encuentra la ciudad de Oruro?"                                   |
| **d. CONDICIÓN**    | Busca elementos que cumplen **uno o varios criterios** específicos (consultas por atributos o espaciales). | "¿Qué poblaciones tienen más de 10,000 habitantes?"                         |
| **e. PATRÓN**       | Busca **regularidades, agrupamientos o distribuciones** espaciales (clústeres, dispersión, etc.).          | "¿Existe un patrón de distribución de los incendios forestales en Bolivia?" |

|Si la pregunta...|Entonces es...|
|---|---|
|Pregunta por **dónde está** algo|**LOCALIZACIÓN**|
|Pregunta por **cómo era antes vs. ahora**|**TENDENCIA**|
|Pregunta por **qué cumple cierta condición**|**CONDICIÓN**|
|Pregunta por **qué pasará si...**|**MODELAMIENTO**|
|Pregunta por **agrupamientos o distribuciones**|**PATRÓN**|

# Union de Datos - Emperejado Borroso
- Varias capas de datos relacionados pueden representar las muchas geografias del mundo real
- En el emparejado borro el factor de relacion entre las diversas capas de información espacias es la `Referencia Geografica`.


# Relación con otros sistemas de información 
SIG es la intersección de estos conjuntos:
- Carotgrafia computarizada
- CAD y AM/FM (Automatic mapping/Facility Managment)
- DBMD
- Sistemas Remotos

# Aplicaciones de un SIG
- Gobiernos 
- Administracion de recursos
- Actividades diarias
- Demografia
- Educación
# Componentes de un SIG
- GENTE: Requiere de un recursos humano adecuado y con conocimientos especializados para crear o usar el sistema
- PRODUCTOS INFORMATICOS: Es lo que quiere obtener el SIG, puede tomar forma de mapas, informes graficos hasta informacion digital que puede transmitirose o o cualquier combinación de estos elementos
- DATOS
- SOFTWARE
- HARDWARE
- PROCEDIMIENTOS


# Tareas de un SIG
Analisis de consultas
Operaciones Espaciales
BUFFER.
- UPDATE
- CUP
- ERASE
- UNION 
- IDENTITY
- INTERSECT


# PROYECCION UTM (Universal Trasverse Mercator)
- El globo esta dividido en 60 fajas al norte y al sur de 6to de longitud cada una.

# PROYECCIONES CONICAS
TANGENTES, SECANTES
# PROYECCIONES CILINDRICAS
Normal, Cilindro , Oblicua

# Sistemas de coordenadas 
### a) Sistemas angulares
### b) Sistema de coordenadas rectangulares o planos
### c) Sistema de coordenadas geográficas (latitud y longitud)
