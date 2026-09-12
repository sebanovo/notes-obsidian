## INTRODUCCION

•Administrar, regular, controlar y planificar las acciones que se desarrollan en un territorio determinado constituye una tarea muy compleja.

•Para justificar la importancia de los Sistemas de Información Geográfica (SIG) y el papel que estos juegan hoy en día, es aproximadamente un 70% de la información que manejamos en cualquier tipo de disciplina esta georreferenciada.  (Información a la cual puede asignarse una posición geográfica).

## CONTINUACION DE LA INTRODUCCION

•El SIG es una tecnología horizontal por la variedad de aplicación industrial e intelectual.

•Las organizaciones usan información respecto a diversos campos. Ej. Inventarios, finanzas, costumbres, habilidades, etc.

•La información geográfica se relaciona con todos estos campos y tiene gran impacto en muchas decisiones sobre ellas.

1. Enviar carros bomberos por rutas mas optimas
2. Programas sociales son aplicados en áreas  donde una necesidad se identifico
3. Estudio de enfermedades por áreas y su propagación

•La geografía es parte de nuestro mundo cotidiano.

## CONTINUACION DE LA INTRODUCCION

•Un SIG describe objetos del mundo real como:

•Su posición respecto a un sistema de coordenadas

•Sus atributos: Características no espaciales

•Su topología: Relaciones espaciales  y como están unidos los objetos geográficos

•Un SIG es capaz de dar respuestas de tipo espacial y topológico relacional de acuerdo a la Base de Datos espacial y alfanumérica.



## HISTORIA DE LOS SIG EN LAS CIVILIZACIONES

- La distribución espacial de los objetos geograficos es inherente a los fenómenos propios de la corteza terrestre, como a los fenómenos artificiales y naturales que sobre ella ocurren.
- Todas las sociedades que han gozado de un grado de civilización han organizado de alguna manera la información espacial o geográfica.
- Los fenicios fueron navegantes, exploradores y estrategas militares que recopilaron información en un formato pictórico, y desarrollaron una cartografía "primitiva“
- Los griegos adquirieron un desarrollo político, cultural y matemático, refinaron las técnicas de abstracción con sus descubrimientos geométricos y aportaron elementos para completar la cartografía utilizando medición de distancias con un modelo matemático
## Representación y manejo de mapas en forma manual

- Los Datos referidos a un espacio geográfico fueron representados con puntos líneas y áreas dibujadas en papel.
- Esta información contiene su propia simbología, colores, figuras, texturas para diferenciar datos, de acuerdo a las características que representa.
- Surgen **problemas** para la recolección y codificación,como ser:

- Perdida de datos: mapas extraviados, quemados, etc.
- Consumo de tiempo para obtener un mapa de un lugar geográfico
- Dificultad en la Recuperación
- Combinación con otros datos espaciales: La escala

- **Resumen**: El manejo de mapas en forma manual no es fácil y  barata, ni confiable

**SOLUCION**:

- Durante las décadas (60 y 70) se empezó a aplicar la tecnología del computador, y la mayoría de programas estuvieron dirigidos hacia la automatización del trabajo cartográfico.
- En 1960 (década)  surge la Cartografía Automatizada
- El proceso de recuperar grandes cantidades de Información Espacial proveniente de diferentes mapas es costoso y difícil.
- En 1969 LAN MACHARG  libro  “Design with Nature” lanza una técnica SCA (Análisis de Aptitud y capacidad de la tierra)
- Los programas SCA son usados para comparar tipos de datos mediante el uso de modelo datos (mapa general.)
- Esta simple técnica dio origen al SIG manual o SIG Analógico.
- Incluye elementos de datos como mapas, hojas transparentes, fotografías aéreas.
## DESARROLLOS CLAVES

Existen 2 desarrollos claves:

**1. Desarrollo de** **Hardvard**

•Se producen en el seno del Harvard Laboratory

•Arq. Howard T. Fisher en 1964

•Usar computadoras para hacer mapas simples

•SYMAP “Symagraphic Mapping Sys”, sobre pone múltiples datos, que permite la entrada de información en forma de puntos, líneas y áreas
![[Pasted image 20260911223750.png]]
## DESARROLLOS CLAVES

**2.Desarrollo de** **Canadá**

•Departamento Federal de Energía y Recursos.

•Este sistema, denominado CGIS (Canadian Geographical Information Systems),  realiza mapas de “Rehabilitación y Desarrollo de las Tierras Agrícolas de CANADA”

•Fue desarrollado a principios de los 60 por Roger Tomlinson: Padre del SIG,

•Quien dio forma a una herramienta que tenia por objeto el manejo de los datos del inventario geográfico canadiense y su análisis para la gestión del territorio rural.

•Primer SIG formalmente desarrollado y hace uso de una base de Datos


## PARTES DE UN SIG

Un SIG convierte datos en información útil mediante un análisis
![[Pasted image 20260911224023.png]]
Los SIG tienen trs partes Datos (Mapas), SIG(Almacenamiento de datos) e Informacion (Productos)


## DEFINICION DE UN SIG
![[Pasted image 20260911224140.png]]

## Operaciones Espaciales y no Espaciales

•Muchos programas de computación como ser: Excel, o paquetes de dibujo como auto CAD pueden manejar datos simples geográficos o espaciales, coordenadas (X,Y). Entonces por que no son considerados como SIG ?

•Un SIG es solamente un SIG si este permite realizar operaciones espaciales sobre los datos

## Consultas No Espaciales

•No requiere almacenar valores de coordenadas como ser Latitud. y Longitud o (x,y) 

•No describe lugares que se relacionan con la ubicación geográfica

•Ejemplos.: 

1. Cual es el numero promedio de gente que trabaja con SIG en la ciudad de Santa Cruz?
2. Cuantos enfermos de Dengue existen en cada departamento.

## Consultas Espaciales

•Solamente son respondidas usando  coordenadas (X,Y) o latitud y longitud

•Solo un SIG puede responder este tipo de consultas-

•Ejemplos:. 

1. Cuanta gente trabaja en SIG en la parte norte de la Ciudad de Santa Cruz?
2. que existe en una posición (X,Y)
3. que existe dentro de un manzano de una ciudad
4. Que lineas de micros pasan por una ubicacion geografica



## Union de Datos


![[Pasted image 20260911224349.png]]


**Emparejado exacto**: es la union de datos como en una base de datos relacional

**Emparejado No Exacto** se dividen en dos:

- Emparejado Jerarquico donde la relacion o union de datos es por jerarquia de datos.
- Emparejado Borroso: esta clase de union de datos es la que utilizan  los SIG

## Union de Datos – Emparejado Borroso

Varias capas de datos relacionados pueden representar las muchas geográfias del mundo real. Ver grafico:
![[Pasted image 20260911224407.png]]



En el gráfico se pueden ver tres capas que representan el mundo real, Customers, Buildings y streets.  
En el emparejado borroso el factor de relación entre las diversas capas de información espacial es la Referencia Geográfica. como en el grafico estas se relacionan mediante la linea roja que tiene una coordenada(x,y) en cada una de las capas.

## PREGUNTAS QUE UN SIG PUEDE RESPONDER

Al SIG se ha descrito en dos formas:

•A través de definiciones formales.

•A través de la habilidad de realizar operaciones espaciales, encadenando datos usando la localización como llave común.

Puede también distinguirse  un SIG listando los tipos de preguntas que este puede ser capaz de responder.

Existen 5 preguntas genéricas que un SIG sofisticado puede responder

## LOCALIZACION O POSICION GEOGRAFICA

Las preguntas que puede responde un SIG en este tipo de preguntas son:

•Que existe en una localización particular

•Una localización puede ser descrita en muchas formas

•Nombre del lugar

•Código postal o telefono

•Referencia Geográfica: Latitud, longitud

Ejemplo: que existe en la localidad con codigo de area 3

               Que existe en la posicion geografica (200000,6700000)

## CONDICION

Este tipo de preguntas necesita de una condición

•Requiere de análisis espacial para responder, al contrario de la anterior.

•Esta pregunta necesita saber la localización que satisface ciertas condiciones.

•Ej. Una sección deforestada < 2000m2

## TENDENCIA

Este tipo de preguntas:

•Involucra las dos primeras

•Desea encontrar las diferencias dentro un área con el tiempo

- Se relaciona con el tiempo

Ejemplo: Cual fue la trayectoria de un rio especifico en el año 1900


## PATRONES

Este tipo de preguntas es mas complicada:

•Pregunta mas sofisticada

•Cuantas anomalías existen que no se ajustan a los patrones y donde están localizadas

•Ejemplo. Si el cáncer es una causa mayor de muerte entre residentes cercanos a una Planta Nuclear


## MODELAMIENTO

Este tipo  de preguntas es mas para realizar simulaciones.

•Preguntas propuestas para determinar que pasa si

•Ejemplos. 

Si un nuevo camino es adicionado a una red 

 Si una substancia tóxica se filtra a la red de agua local.

•Para responder este tipo de preguntas se requiere de datos geográficos así como otra información descriptiva


## Relacion con otros sistemas de informacion

LOS SIG SE RELACIONAN CON TODAS LOS SISTEMAS DE INFORMACIÓN, UTILIZANDO SUS CARACTERÍSTICAS, Y ESPECIALMENTE CON LOS SIGUIENTES SISTEMAS:
![[Pasted image 20260911224531.png]]



## CARTOGRAFIA COMPUTARIZADA

**La Cartografía computarizada:**

Producen mapas con buena salida vectorial (formato), lo importante de estos sistemas es el despliegue de los datos. 

No es importante el manejo y análisis de los datos geograficos


## LOS DBMS

**DBMS**

Un DBMS trabajan sobre todo con datos  no espaciales (alfanumericos), incluyendo datos geográficos. 

Tiene limitaciones al momento del despliegue gráfico, a realizar el análisis de tipo espacial. 

Los SIG manejan sus tablas de datos no espaciales en un nivel básico.

## CAD Y AM/FM

**CAD y AM/FM**

(Automatic mapping/Facility Management)

Los elementos básicos de datos de los CAD son: Line, Circles and arcs, lines, symbols, text y otros. Estos están referenciados a un sistema de coordenadas (GRILLA).

Los datos en un CAD están organizados en “Layers” .

Ejemplos de esos sistemas son la representación de redes de agua, calles, electricidad, etc

## RELACION CON SISTEMAS REMOTOS

**Sistemas  Remotos**

Se definen como la técnica de adquisición y procesamiento digital posterior de los datos de la superficie terrestre desde sensores instalados en plataformas espaciales (satelites, drones), en virtud de la interacción electromagnética existente entre la tierra y el sensor.

Como resultado de estos sistemas estan las imagenes satelitales de diversos formatos (Hertz, landsat, ikonos, etc)

En SIG esta informacion se denomina RASTER


## Aplicaciones de un SIG

•E**n Gobiernos**

•Planificación, zonificación, seguridad publica, valoración de tierras

•**Administración de Recursos**

•Pesca y planificación de la fauna, agricultura

•Manejo de recursos minerales y energéticos

•**Actividades diarias**

•Electricidad, agua, gas, petróleo, telecomunicaciones, TV cable

•**Demografía**

•Análisis de mercado, Salud

•**Educación**

•Universidades, laboratorios, bibliotecas, Institutos de investigación

  

**CONCLUSION**: Un SIG es una herramienta de propósito general.


## Componentes de un SIG

LOS COMPONENTES DE UN SIG SON: PRODUCTOS INFORMATIVOS, DATOS, SOFTWARE, HARWARE,PROCEDIMIENTOS Y GENTE
![[Pasted image 20260911224730.png]]
## Productos Informativos

- Es el resultado que se quiere obtener del SIG
- Puede tomar la forma de mapas, informes, gráficos, listas, información digital que puede transmitirse o cualquier combinación de estos elementos.
- Lo importante es tener bien identificados estos productos con suficiente claridad para saber que datos almacenar en las Bases de Datos
## Datos

- Es uno de los componentes más importantes de los SIG y los más difíciles de adquirir, pues se requiere de un largo y costoso proceso de adquisición.
- Al saber que productos informativos debemos tener como resultados de los SIG se puede planificar la adquisición de datos que necesite o que ya exista
- Que puede crear a partir de fuentes existentes
- Que grados de precisión y escala requerirá para los mapas
- El Formato de los datos es un factor para elegir el software SIG

## Software

- Los software proporcionan las funciones necesarias para realizar el análisis espacial y no espacial, almacenamiento y creación de los productos informativos que se desea
- Este componente Tiene dos procesos: ingreso de datos espaciales y codificación de atributos.
- El software SIG debe tener Una interfaz gráfica de usuario para facilitar el acceso a las herramientas de análisis espacial.

## Hardware

- De acuerdo a los Productos informativos que se desea elaborar o conseguir mediante un SIG, se debe necesitar los siguientes tipos de Hardware:

- Servidores
- Computadores
- Plotters o Impresoras de mapas
- Scanners de dimensiones grandes
- Red
- Ancho de banda de conexión a internet
- Otros

## Procedimientos

- Un SIG debe de operar de acuerdo a un PLAN (Metodos) bien definido y a estándares de la empresa, las cuales son modelos y prácticas de operación únicas en cada organización
- Se refieren a la manera como las personas realizan sus trabajos y los cambios que tendrán que adoptar para trabajar con un SIG.
- Plan de migración para facilitar la transición del método antiguo al nuevo
- Tener en cuenta como los sistemas existentes coexistirán con el SIG.

## Recursos Humanos

- Requiere de un recursos humano adecuado y con conocimientos especializados para crear o usar el sistema
- Sin el personal experto, la información se desactualiza y se maneja erróneamente.
- El hardware y el software no se manipula en todo su potencial.
- Entre los usuarios del SIG se encuentran especialistas técnicos, que diseñan y mantienen el sistema para los que se utilicen diariamente.
- intervienen mucha gente con diferentes especialidades como ser geógrafos, urbanistas, geólogos, de medio ambiente, informáticos y otros

## COMO FUNCIONAN LOS SIG

•El Sistema de Información Geográfica almacena la información gráfica en capas temáticas que pueden enlazarse geográficamente,

  

•Cada capa se encuentra enlazada además con una o varias bases de datos, utilizando el concepto relacional para la consulta de los mismos.

  

•Las capas se relacionan con las tablas mediante un identificador
![[Pasted image 20260911224830.png]]


![[Pasted image 20260911224939.png]]



#  LAS TAREAS DE UN SIG
## INGRESO Y VERIFICACION DE LA INFORMACION

1.- Entrada de datos Espaciales (Construcción base de datos geográfica)  

- Este proceso de abstracción tiene diversos niveles, comienza con la concepción de la estructura de la base de datos, generalmente en capas
- Existen cinco métodos básicos de entrada de datos Espaciales:

- ﻿Coordenadas usando Coordenadas Geometricas
- Conversión de Información Digital existente
- Scanner
- Digitalizador Manual
- Digitalización  Automático

2.- Entrada de datos no espaciales  

- Ingreso de datos de atributos en archivos texto a un motor de base de datos, previamente modelado  y diseñado el modelo de datos descriptivo.

3.-Unión de datos espaciales y no espaciales

- Se enlazan los datos espaciales con los datos alfanuméricos o de atributos o descriptivos.
- También se verifican la exactitud de la relación entre los datos espaciales y no espaciales

## Transformación y manipulación de la información

Engloba dos clases de operaciones

•Transformación  necesaria para corregir errores de la Información para actualizarla o para adecuarla a otro conjunto de Información

•Transformaciones que se deben realizar, según el método de análisis que se emplee para dar respuestas a las interrogantes previamente plantadas

Estas transformaciones pueden operar en los aspectos espaciales y no espaciales de la Informacion. Por separado o conjunto.  

  

**Ejemplos**: Cambios de escala, cambios de proyecciones, recuperación lógica de la Informacion. , formatos, área y perímetros.


## Integracion y Modelado

•Los SIG integran la información existente de datos espaciales y no espaciales formando modelos que representan el mundo real.

•El modelado en los SIG se realiza sobreponiendo información espacial (Superposición de Mapas).  Implica:

-  Proceso geométrico
- Topológico
- Integración de capas de Información.

•-El producto es un mapa nuevo.

  

La superposición de mapas o modelado además de ser una herramienta analítica, también es usada para una serie de procesos de manipulación


## Manejo y Administración

**§** En proyectos pequeños puede que sea posible almacenar la información geográfica como archivos simples.

**§** Sin embargo, llega un punto en el que el volumen de los datos aumenta, en esos casos es mejor la utilización de un sistema de administración de base de datos (DBMS).

## Análisis de Consultas

Los SIG pueden realizar el Análisis de consultas Espaciales y no espaciales

  

**Recuperación y Presentación de la Información**

•Se refiere a la forma de extraer y mostrar los productos

**a)Especificación Geométrica: (ver siguiente parte)**

- Se determina un área específica, de forma cualquiera y se pide toda la información de esa área.
- De una determinada área se pide toda la información o ítems que cumplan una condición.
- Ejemplo. Provincias de  SCZ   >  de un valor .

**b)Especificación Descriptiva:**

- Se elige una Base de Datos referente a un área y se pide toda la información o atributos de los registros. 
- De una Base de Datos elegida de un área se seleccionan aquellos registros que cumplan con determinadas condiciones


## Análisis de Consultas (Continuación)

Existen operaciones espaciales como: Unión, intersección, identidad,, clip, erase , update

Pero la mas importante es BUFFER: Consulta información dentro de un area puntual que genera una area de influencia circular, lineal, y polígono. Asi como se ve en la figura


![[Pasted image 20260911225035.png]]



![[Pasted image 20260911225413.png]]

# LECCION # 2
# INTRODUCCION
En esta leccion aprenderemos sobre:

1. •Elementos básico que debe tener un mapa en papel
    
    - •Objetos  geográficos
    - •Descripción de los objetos
    - •Escala
    
    - •Sistema de coordenadas
2. •Uso de un computador para manejar mapas:
    
    - •Información espacial
    
    - •Información descriptiva

## Concepto de Mapa Base

Un **Mapa Base** es el mapa principal donde se realizara todo el trabajo de SIG.

Un Mapa muestra la siguiente información de los objetos o características geográficas :

1. **Información Espacial**

- Describe o muestra la localización o posición del objeto geográfico
- Muestra la forma del objeto geográfico
- Muestra la relación que existe entre objetos geográficos como por ejemplo: Que esta al lado derecho de un rio, o que objeto se encuentra dentro de otro objeto geográfico.

3. **Información Descriptiva**

4. Es la información descriptiva de los objetos geográficos que se encuentran en el mapa

Ejemplo:

Se muestra a continuación un mapa con su información Espacial y Descriptiva

- **Información espacial** la forma de los departamentos y la posición de los rios
- **Información descriptiva:** los nombres de los departamentos, nombres de los países que rodean Bolivia y el cuadro de referencias

En los mapas existen también información adicional como ser titulo del Mapa, escala del mapa, gráfico del norte geográfico, y el reticulado del sistema de coordenadas.


![[Pasted image 20260911225514.png]]

## Representación de objetos geograficos

Características u Objetos Geográficas son objetos localizados sobre o cerca de la superficie de la tierra.

Esos objetos geográficos pueden:

- **Ocurrir en forma natura**l, donde no intervino la mano del hombre, como ser: montañas, lagos, volcanes, etc.
- **Ser construcciones**, donde intervino la mano del hombre, como ser: puentes, caminos, ciudades, aeropuertos,etc.
- **Ser subdivisiones de la tierra**, como ser:  países departamentos, provincias, etc.

## Componentes de los Objetos Geográficos

Los Objetos o características Geográficos tienen los siguientes componentes:

1. **Geometría**: que muestra la forma del objeto geográfico
2. **Atributos**: Muestra la descripción del objeto geográfico, como ser nombre del departamento.
3. **Comportamiento**: Muestra la relación entre objetos geográficos, como ser: si una calle intersecta una manzana, si un rio atraviesa un departamento.
![[Pasted image 20260911225733.png]]

# USO DE MAPAS PARA REPRESENTAR DATOS GEOGRAFICOS


## COMO LOS MAPA TRANSMITEN INFORMACIÓN GEOGRÁFICA

•Los mapas modelan el mundo real con Puntos, líneas, áreas y superficies

•También utilizan símbolos y etiquetas para hacer una descripción de los objetos  geograficos mostrados en el mapa:
![[Pasted image 20260911225851.png]]

## COMO LOS MAPAS TRANSMITEN INFORMACION DESCRIPTIVA

Los mapa transmiten información descriptiva de los objetos geograficos usando símbolos y etiquetas como ser:

- Caminos son dibujados con

- varios anchos de línea,
- colores para representar diferentes clases de caminos

- Ríos y lagos son dibujados usando color azul para representar agua
- El uso de Símbolos especiales denotan características especificas de un objeto geográfico.
- Las Calles son etiquetadas con nombres
- Las Construcciones especiales son etiquetados con sus nombres

En el,gráfico mostrado  se puede observar  los nombres de los departamentos y colores que diferencian a cada departamento, también se representan ríos de color azul, como tambien las fronteras de los departamentos con lineas segmentadas

![[Pasted image 20260911225932.png]]


## Como los mapas transmiten relaciones Espaciales

•En los mapas las relaciones espaciales son importantes

•Ayudan a entender situaciones y realizar la tomas de decisiones.

•La relación entre características u objetos geográficas se llama Relación Espacial

•Las Relaciones espaciales en un mapa son implícitas, por ejemplo:

–Que característica geográfica **conecta** a otro

–Cual característica geográfica es **adyacente** a otro

–Cual característica geográfica **esta contenida** en un área

–Cual característica geográfica **intercepta** a otro

–Cual característica geográfica **esta cerca** de otro

Ejemplo: Que avenidas **interceptan** el Segundo anillo

QUE RELACION ESPACIAL CORRESPONDE A LA SIGUIENTE SITUACION DE SANTA CRUZ Y BOLIVIA

# CONCEPTOS ADICIONALES DE MAPAS

•La distancia es una parte importante de las relaciones entre características geográficas.

•A menudo se necesita conocer la distancia de un objeto a otro.

•Ej. Distancia entre un Aeropuerto y un Hotel.

•Para convertir una medida de mapa a distancia del mundo real, se debe conocer la escala del mapa

•La Escala es la relación entre la distancia en un mapa y la distancia correspondiente en el mundo real. Ej. 1:100000 (Que significa un cm en papel hace cien mil cm en el mundo real)

•La escala tiene efecto en la resolución y precisión del mapa.

A CONTINUACIÓN EJEMPLOS DE LA VARIACIÓN DE LA ESCALA EN UN MAPA QUE AFECTA A LOS DOS EJES X y Y
![[Pasted image 20260911210730.png|478]]
### CALCULO DE LA ESCALA DE UN MAPA

Calcularemos la escala de un mapa con los siguientes datos:

•Distancia en papel:  Dp = 25 cm

•Distancia en el mundo real: Dr=50 Km.

**DESARROLLO DEL CALCULO:**

•Según la definición:  Escala = Dp / Dr

•Escala:  25 cm / 5000000 cm

•Dividir  el numerador y el denominador entre 25 cm se tiene

•Escala  1 / 200000 (resutado del calculo)

•Notaciones:

•Escala Texto     1:200000

•Escala Grafica
![[Pasted image 20260911210901.png|173]]
## EJEMPLO![[Pasted image 20260911211312.png]]


# LECCION #3
## INTRODUCCION A REPRESENTAR INFORMACION GEOGRAFICA

En los Sistemas de Informacion Geografica existen tres modelos para representar información geográfica en un computador:

  

1. Modelo de datos vector (MDV)
2. Modelo de datos raster (MDR)
3. Modelo TIN (Triangulated irregular network)

En esta leccion veremos el modelo vector y el modelo raster

## MODELO DE DATOS VECTOR (MDV)

El MDV representa objetos o características geográficas en una computadora similares a la forma en que los mapas son hechos.   
Utiliza : puntos, líneas, y áreas

Cada posición geográfica es registrada como una sola coordenada (x,y)

A continuación _se muestra como se guarda las coordenadas como puntos lineas y areas:_

•**Puntos** : Es registrado como una sola coordenada (x,y)

•**Líneas** : Son registrados como una serie de coordenadas (x,y)

•**Areas**: Son registrados como una serie de coordenadas (x,y) y definiendo segmentos que definen un área o polígono.

Esta lista de coordenadas representa como los objetos geográficos son almacenadas en un computadora como un conjunto de coordenadas (x,y).
![[Pasted image 20260911212554.png]]
## MDV (CONTINUACION)
Una lista de coordenadas para cada característica es asociada con el numero de identificación.

![[Pasted image 20260911212914.png]]
## ESTRUCTURA DE DATOS ARCO-NODO

•Las fronteras comunes de dos parcelas o polígonos adyacentes no deben  repetirse  cuando se dibuja sobre un mapa.

•Esto se aplica para almacenar fronteras comunes en un computadora

•Donde sea se debe evitar la posible duplicación de datos

•Repetir las coordenadas de un punto compartido por un numero de líneas es ineficiente

•Seria almacenado muchas veces

•Entre polígonos adyacentes almacenar cada polígono como una vuelta cerrada de coordenadas es también ineficiente.

•La Manera mas eficiente para almacenar datos vector es la estructura Arco - Nodo

•La estructura de datos Arco-Nodo almacena y referencia datos tal que los nodos construyen arcos y los arcos construyen polígonos.

•Los Nodos definen los dos puntos inicial y final de un arco

•Los nodos pueden o no pueden conectar a dos o mas arcos

•Arco es el segmento de línea entre dos nodos

•Un arco esta compuesto de sus dos nodos y una serie ordenada de puntos los cuales definen su forma, vértices.![[Pasted image 20260911213307.png]]


## TOPOLOGIA

Es una rama de la matemática que estudia relaciones espaciales

En SIG es una herramienta que permite mantener relaciones espaciales entre objetos geográficas

De esta forma no habrá huecos entre fronteras, los arcos estarán conectados o las superficies no se solaparan.

La estructura de datos Arco-Nodo soporta tres conceptos:

•Conectividad: Arcos conectan a cada uno de los nodos.

•Definición de área: Arcos que conectan alrededor de un área definen un polígono

•Contigüidad: Los arcos tiene dirección y lados derecho e izquierdo

## CONECTIVIDAD

•Un arco es definido por dos nodos finales, From-node y To-node

•La Topología arco-nodo es soportado a través de una lista arco-nodo  

•Permite identificar una ruta al aeropuerto o Conectar arroyos con ríos![[Pasted image 20260911213712.png]]

## DEFINICION DE AREA

•Muchos de los objetos que deseamos representar cubre un área sobre la superficie de la tierra. Ejemplos: Lagos, etc.

•Un área es representada en el MDV por uno o mas limites definiendo polígono

•La estructura de datos arco-nodo representa polígonos como una lista ordenada de arcos mas que una figura cerrada de coordenadas x,y.

•Esto es denominado Topología Polígono-arco![[Pasted image 20260911213858.png]]


## CONTIGUIDAD

•Dos objetos geográficas que comparten un limite son llamados adyacentes

•La contigüidad permite al MDV determinar la adyacencia

•El from-node y el to-node definen un arco.

•Esto indica la dirección de un arco para que puedan ser identificados los polígonos izquierdo y derecho

•La topología Izquierdo-derecho se refiere a los polígonos del lado izquierdo y derecho de un arco

![[Pasted image 20260911214335.png]]
## EXTENSIONES DEL MDV

•Otras asociaciones entre características geográficas son importantes para modelar:

  

**_"Una característica geográfica puede ser compuesta de otras características"_**

•Ej. Un estado conjunto de ciudades, Una ruta de bus puede ser una asociación de secciones de calles

**_"La misma característica geográfica puede cambiar con el tiempo y un rastreo histórico de los cambios es importante"_**

•Ej. Una parcela es subdividida y la forma original y la información de atributos debe ser mantenida. El flujo de trafico a lo largo de una ruta cambia en diferentes periodos de tiempo

**_"Las características geográficas de la misma clase pueden sobreponerse"_**

•Ej Aplicado al control de las especies, áreas de mercados de competencia, dos rutas de bus usan la misma sección de calle

Existen dos extensiones en el MDV: Regiones y Rutas

## REGIONES

•Las Regiones soportan el modelamiento de complejas relaciones entre polígonos

•El bloque de construcción de un polígono es el arco y el bloque de construcción de una region es el polígono

•Una región es representada por un conjunto de polígonos

•Los polígonos en el MDV no se sobreponen y cubren completamente el área representada

•En una región los polígonos pueden sobreponerse.![[Pasted image 20260911215044.png]]

Una premisa de polígono es que cada objeto geográfica es representada por un polígono

•Una sola característica u objeto geográfico puede ser representada por varios polígonos

•Ej . Islas de Hawai![[Pasted image 20260911215051.png]]

•La construcción de regiones con polígonos es similar a la construcción de polígonos de arcos

•Una región es una lista de polígonos

•El orden de los polígonos no es significante

•Como los polígonos comparten una arco, también las regiones comparten polígonos donde se sobreponen![[Pasted image 20260911215057.png]]

## RUTAS

•Define caminos a lo largo de un conjunto existente de objetos geográficos lineales.

•Las Routes estan basados en arcos.

Ejemplo: definir una ruta desde un hotel hasta el aeropuerto sobre una red de caminos

![[Pasted image 20260911215240.png]]


![[Pasted image 20260911215749.png]]



## INTRODUCCION AL MDR

•El enfoque en el Modelo de Datos Raster (MDR) esta en la localización

•El MDR es mas como una fotografía que un mapa.

•Una foto esta hecha de una serie de _dots_ de diferentes colores

•El MDR trabaja de la misma manera: Usa una Grilla regular de _dots, cells,  pixels_ con valores

•La Imagen almacenada en computadora es usando el MDR.

•Existen 3 formas de interpretar una foto:

•**Clasificar** cada punto como perteneciente a algún grupo de similares características

•**Medir** el valor de su color o sombra de grises

•**Definir** el pixel relativo a un punto de referencia conocida. Ej. Bajo el nivel del mar![[Pasted image 20260911215846.png]]


•Estas tres interpretaciones pueden ser usados en el MDR.

•El valor de la celda representa una clasificación, ejemplo un  tipo de vegetación

•En el MDR, cada localización es representada como una celda.

•La matriz de celdas, que es organizado por filas y columnas, es llamada una grilla.

•Cada fila contiene un grupo de celdas con valores representando un fenómeno geográfico.

•Los valores de las celdas son números, representan datos nominales tales como clases de uso de suelos, intensidad de luz, calor, etc.![[Pasted image 20260911215920.png]]


## REPRESENTACIÓN DE OBJETOS GEOGRÁFICOS EN MDR

•El MDR puede representar características u objetos geográficos discretas de puntos, líneas y áreas.

»Una característica punto es representado como un valor en una sola celda

»Una característica lineal como una serie de celdas conectadas.

»Una característica de área como un grupo de celdas conectadas mostrando la forma.

![[Pasted image 20260911220938.png|439]]
![[Pasted image 20260911221048.png]]



# USANDO LOS MODELOS MDV Y MDR JUNTOS
## INTEGRACION DE LOS MODELOS MDV YMDR

•El MVD y el MDR son poderosas formas de modelar la tierra usando un computador

•Cada uno usa el sistema de coordenadas cartesianas para definir localizaciones o posiciones

•Adoptan una proyección de mapa, escalas y ajustan coordenadas compartiendo un origen común
![[Pasted image 20260911221112.png]]


## COMPARACIÓN DE MODELOS ESPACIALES MDV Y MDR
![[Pasted image 20260911221144.png]]



## RASTERIZACION Y VECTORIZACION

•**RASTERIZACION**: Conversion de Modelo Vector  a  Modelo Raster

• VECTORIZACION: Conversión del Modelo Raster  a  Modelo Vector


![[Pasted image 20260911221257.png]]



# LECCION4.- REPRESENTANDO INFORMACION DESCRIPTIVA EN UN COMPUTADOR

## INTRODUCCION

En una lección anterior vimos que un Mapa tiene dos tipos de información: 

- **Espacial**: Muestra los objetos geográficos 
- **Descriptiva**: Hace una descripción de la información de los objetos geográficos. 

En esta lección examinaremos los métodos disponibles para representar la información descriptiva acerca de los objeto o características geográficas.

También examinaremos como el dato descriptivo es organizado y como es encadenado al objeto geográfico en un modelo de datos espacial.

Los atributos o información descriptiva asociados con objetos geográficos son almacenadas en el computador de una forma similar a como son almacenadas las coordenadas.

## TABLA DE ATRIBUTOS

En ARCGIS se almacena la Información descriptiva en archivos .dbf. Estos archivos son conocidos como Tabla de Atributos.

También se pueden acceder a Motores de Bases de Datos, como ORACLE, Informix, SYBASE, etc.

En la gráfica se puede observar que una capa de información geográfica puede conectarse simultáneamente con varias bases de datos.![[Pasted image 20260911221415.png]]


## MODELO GEORELACIONAL

- En mapas, los símbolos y textos comunican información descriptiva
- Los mapas son herramientas poderosas para referenciar información.
- El modelo georelacional es un concepto aplicado al modelo de datos espacial.
- El poder del SIG es capaz de encadenar el dato espacial y el dato tabular o descriptivo
- Mantener la conexión entre las características u objetos geograficos y sus datos descriptivos, es referido como un **Modelo de Datos Georelacional.**

Próximo paso es entender como un LINK es creado entre la definición espacial de objetos geograficos y sus registros de atributos correspondientes. La Respuesta es bastante simple:

- El único identificador de una característica asocia los atributos con las coordenadas de la característica
- Mantiene una correspondencia de uno-a-uno entre los registros espaciales y los registros atributos
- El único identificador es almacenado físicamente en dos lugares:

- En los archivos conteniendo los X,Y
- En la Tabla de atributos

- Una vez hecha la conexión , se puede desplegar la información de atributos o crear un mapa basado en esos atributos, utilizando los procesos Relate o Links vs Join
- Importante concepto relacional: Uno a muchos

![[Pasted image 20260911223038.png]]
![[Pasted image 20260911221504.png]]



# Lección 5 ArcGIS

## INTRODUCCION AL ARCGIS

•ArcGIS es un sistema que permite recopilar, organizar, administrar, analizar, compartir y distribuir información geográfica.

•ArcGIS es utilizada por personas de todo el mundo para poner el conocimiento geográfico al servicio de los sectores del gobierno, empresas, ciencia, educación y los medios.

•ArcGIS permite publicar la información geográfica para que esté accesible para cualquier usuario. El sistema está disponible en cualquier lugar a través de navegadores Web, dispositivos móviles como smartphones y equipos de escritorio.

•Se puede pensar en el sistema ArcGIS como en una infraestructura para elaborar mapas y poner la información geográfica a disposición de los usuarios dentro de un departamento, por toda una organización, entre varias organizaciones y comunidades de usuarios o en Internet, para cualquier usuario interesado en acceder a ella.
![[Pasted image 20260911223147.png]]



## QUE SE PUEDE HACER CON UN ARCGIS

**Crear, compartir y utilizar mapas inteligentes**

•ArcGIS permite crear una variedad de mapas, entre ellos, mapas Web accesibles en navegadores y dispositivos móviles, diseños de mapa impresos de gran formato, atlas, mapas integrados en aplicaciones, etc. Independientemente de cómo se publica, un mapa de ArcGIS es un mapa inteligente que muestra, integra y sintetiza capas de información geográfica y descriptiva de diversas fuentes.

**Compilar información geográfica**

•ArcGIS permite sintetizar datos de diversas fuentes en una misma vista geográfica unificada. Estas fuentes de datos incluyen información de bases de datos geográficas, datos tabulares de sistemas de administración de bases de datos (DBMS) y otros sistemas empresariales, archivos, hojas de cálculo, vídeos y fotos con geoetiquetas, KML, CAD Data, fuentes en directo de sensores, imágenes aéreas y de satélite, etc

•Crear y administrar bases de datos geográficas

•Las bases de datos geográficas son la piedra angular del trabajo SIG profesional. Una base de datos geográfica hace posible que la información geográfica se almacene en un formato estructurado que simplifica la administración, la actualización, la reutilización y el uso compartido de los datos.

**Resolver problemas con el análisis espacial**

•El objetivo que persigue es derivar nueva información de los datos existentes para permitir una mejor toma de decisiones. 

**Crear aplicaciones basadas en mapas**

•Al crear aplicaciones en la Web, en equipos de escritorio, smartphones, dispositivos tablet y otros dispositivos móviles; los mapas, los datos, las herramientas se convierten en productos de información que cualquiera puede usar. Esto prácticamente permite poner los mapas y las funcionalidades al servicio de otras personas en una amplia variedad de situaciones.

**Dar a conocer y compartir información mediante la geografía y la visualización**


## ARCGIS DISPONIBLE

Los profesionales de SIG utilizan ArcGIS for Desktop y ArcGIS for Server para crear y compartir contenido enriquecido e información geográfica.

Administran esta información on-line: en la red de su empresa o en la infraestructura basada en la nube de ArcGIS Online.

Además, comparten esta información con muy diversos tipos de clientes, dispositivos y sitios Web.


![[Pasted image 20260911223227.png]]


## ARCGIS PARA DESARROLLADORES

Los desarrolladores y diseñadores pueden crear extraordinarias aplicaciones utilizando cualquiera de los mapas y los servicios relacionados de ArcGIS, entre los que se incluyen funciones avanzadas proporcionadas por los servicios de geoprocesamiento.

Es posible acceder a todo el contenido geográfico de ArcGIS directamente mediante aplicaciones que utilizan el protocolo abierto REST.

Los desarrolladores pueden crear innovadoras aplicaciones centradas en mapas que proporcionan nuevas formas de acceso a la información geográfica para el nuevo público, o incorporar funciones de SIG en las aplicaciones existentes.

 ArcGIS ofrece API gratuitas para JavaScript, Flex, Silverlight y para los principales dispositivos móviles como Apple iOS, Android, Windows Phone y Windows Mobile.

Los desarrolladores ofrecen sus ideas. Y a partir de estas, se consiguen unas extraordinarias aplicaciones.
![[Pasted image 20260911223242.png]]


## INICIOS DEL ARCGIS

•El último producto comercializado por la empresa ESRI (Environmental Systems Research Institute) es el ArcGIS.

•Este nombre se usa tanto para designar al conjunto de aplicaciones SIG de esta empresa (ArcGIS System) como  parte de sus productos (ArcGIS Desktop). El esquema que ofrece la compañía es el siguiente

•SIG antiguos de esta compañía:

•**Arc/Info** (hasta la versión 7.x): lanzado en 1981, este SIG es famoso internacionalmente por su capacidad de manejo y análisis de mapas vectoriales. Hoy en día se comercializa como parte del producto ArcGIS con el nombre de Arc/Info Workstation (Arc/Info 8.x y siguientes).

•**ArcView**: (hasta la versión 3.x): lanzado en 1992, nació como SIG de visualización y consulta sin capacidades de análisis. Las versiones 3.x, sin embargo, ya disponían de módulos de análisis. Este SIG se convirtió en el número uno del mercado y es el que evolucionó en el ArcGIS moderno.

•ArcGIS nace en 2001 con la versión 8.1, como evolución natural de ArcView y, opcionalmente, incorporando Arc/Info con el apellido de Workstation. Complicando las cosas, la compañía ofrece tres versiones del mismo producto ArcGIS (Desktop):


## APLICACIONES COMUNES DEL ARCGIS

•ArcGIS, en cualquiera de sus modalidades está integrado a su vez por tres aplicaciones comunes: ArcMap, ArcCatalog y ArcToolbox.

•**Arc Map**, es la aplicación central de ArcGIS, permite realizar tareas con los mapas y sus datos relacionados: visualización, edición, búsquedas, análisis, gráficos y reportes.

•**ArcCatalog**, ayuda a organizar y gestionar los archivos de datos e información SIG, por medio de herramientas de exploración, administración, previsualización de archivos y gestión de los metadatos.

•**ArcToolbox**, contiene herramientas para el geoprocesamiento, esto es: análisis, gestión y conversión de formatos y proyecciones de los mapas.

![[Pasted image 20260911223306.png]]

## APLICACIONES ESPECIALIZADAS DEL ARCGIS

Existen también aplicaciones especializadas que pueden adicionarse al entorno ArcGIS, denominadas extensiones, las más importantes son: Spatial Analyst, 3D Analyst y Geostatistical Analyst.

•**Spatial Analyst,** es factible realizar operaciones de modelación y análisis sobre archivos gráficos de tipo raster.

•**3D Analyst,** permite visualizar y analizar superficies tridimensionales, creando perspectivas realisticas a partir de modelos digitales de terreno (MDT).

• **Geostatistical Analyst,** puede generar, a partir de puntos georeferenciados, superficies continuas producto de un análisis estadístico de tipo descriptivo o predictivo de determinados fenómenos espaciales.


## INICIANDO ARCMAP

Para ejecutar el ArcMap usaremos la siguiente secuencia de menú desde Windows: Inicio>Todos los Programas> ArcGIS >ArcMap.
![[Pasted image 20260911223505.png]]

•Aparece la ventana de la Figura de abajo. Los archivos de ArcMap o documento de ArcMap, tienen la extensión .mxd. Se puede crear un nuevo documento de ArcMap partiendo de cero, o utilizar una plantilla, o bien abrir un documento previamente creado
![[Pasted image 20260911223515.png]]

•Para abrir un proyecto ejecutar de la barra de menú la opción file/abrir.

•Luego dirigirse ala carpeta donde se encuentra el proyecto y abrir

![[Pasted image 20260911223527.png]]

•El interfaz que por defecto del Arcmap muestra lo siguiente:
![[Pasted image 20260911223537.png]]

Ejecutando propiedad es de una capa activa del menú contextual

![[Pasted image 20260911223544.png]]