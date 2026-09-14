# INTRODUCCIÓN

- Administrar, regular, controlar y planificar las acciones que se desarrollan en un territorio determinado constituye una tarea muy compleja.

- Para justificar la importancia de los Sistemas de Información Geográfica (SIG) y el papel que estos juegan hoy en día, aproximadamente un 70% de la información que manejamos en cualquier tipo de disciplina está georreferenciada (información a la cual puede asignarse una posición geográfica).

## CONTINUACIÓN DE LA INTRODUCCIÓN

- El SIG es una tecnología horizontal por la variedad de aplicación industrial e intelectual.

- Las organizaciones usan información respecto a diversos campos. Ej.: inventarios, finanzas, costumbres, habilidades, etc.

- La información geográfica se relaciona con todos estos campos y tiene gran impacto en muchas decisiones sobre ellas.

1. Enviar carros bomberos por rutas más óptimas.
2. Programas sociales son aplicados en áreas donde se identificó una necesidad.
3. Estudio de enfermedades por áreas y su propagación.

- La geografía es parte de nuestro mundo cotidiano.

## CONTINUACIÓN DE LA INTRODUCCIÓN

- Un SIG describe objetos del mundo real como:

- Su posición respecto a un sistema de coordenadas.
- Sus atributos: características no espaciales.
- Su topología: relaciones espaciales y cómo están unidos los objetos geográficos.

- Un SIG es capaz de dar respuestas de tipo espacial y topológico-relacional de acuerdo con la base de datos espacial y alfanumérica.

## HISTORIA DE LOS SIG EN LAS CIVILIZACIONES

- La distribución espacial de los objetos geográficos es inherente a los fenómenos propios de la corteza terrestre, como a los fenómenos artificiales y naturales que sobre ella ocurren.
- Todas las sociedades que han gozado de un grado de civilización han organizado de alguna manera la información espacial o geográfica.
- Los fenicios fueron navegantes, exploradores y estrategas militares que recopilaron información en un formato pictórico y desarrollaron una cartografía "primitiva".
- Los griegos adquirieron un desarrollo político, cultural y matemático, refinaron las técnicas de abstracción con sus descubrimientos geométricos y aportaron elementos para completar la cartografía utilizando medición de distancias con un modelo matemático.

## REPRESENTACIÓN Y MANEJO DE MAPAS EN FORMA MANUAL

- Los datos referidos a un espacio geográfico fueron representados con puntos, líneas y áreas dibujadas en papel.
- Esta información contiene su propia simbología, colores, figuras, texturas para diferenciar datos, de acuerdo con las características que representa.
- Surgen **problemas** para la recolección y codificación, como ser:

- Pérdida de datos: mapas extraviados, quemados, etc.
- Consumo de tiempo para obtener un mapa de un lugar geográfico.
- Dificultad en la recuperación.
- Combinación con otros datos espaciales: la escala.

- **Resumen**: el manejo de mapas en forma manual no es fácil, ni barato, ni confiable.

**SOLUCIÓN**:

- Durante las décadas de 1960 y 1970 se empezó a aplicar la tecnología del computador, y la mayoría de programas estuvieron dirigidos hacia la automatización del trabajo cartográfico.
- En 1960 surge la Cartografía Automatizada.
- El proceso de recuperar grandes cantidades de información espacial proveniente de diferentes mapas es costoso y difícil.
- En 1969, Ian McHarg, en su libro "Design with Nature", lanza una técnica SCA (Análisis de Aptitud y Capacidad de la Tierra).
- Los programas SCA son usados para comparar tipos de datos mediante el uso de un modelo de datos (mapa general).
- Esta simple técnica dio origen al SIG manual o SIG Analógico.
- Incluye elementos de datos como mapas, hojas transparentes, fotografías aéreas.

## DESARROLLOS CLAVES

Existen 2 desarrollos claves:

**1. Desarrollo de Harvard**

- Se producen en el seno del Harvard Laboratory.
- Arq. Howard T. Fisher en 1964.
- Usar computadoras para hacer mapas simples.
- SYMAP "Symagraphic Mapping System", sobrepone múltiples datos, que permite la entrada de información en forma de puntos, líneas y áreas.

![[Pasted image 20260911223750.png]]

## DESARROLLOS CLAVES

**2. Desarrollo de Canadá**

- Departamento Federal de Energía y Recursos.
- Este sistema, denominado CGIS (Canadian Geographical Information Systems), realiza mapas de "Rehabilitación y Desarrollo de las Tierras Agrícolas de Canadá".
- Fue desarrollado a principios de los 60 por Roger Tomlinson: Padre del SIG.
- Quien dio forma a una herramienta que tenía por objeto el manejo de los datos del inventario geográfico canadiense y su análisis para la gestión del territorio rural.
- Primer SIG formalmente desarrollado y hace uso de una base de datos.

## PARTES DE UN SIG

Un SIG convierte datos en información útil mediante un análisis.

![[Pasted image 20260911224023.png]]

Los SIG tienen tres partes: Datos (Mapas), SIG (Almacenamiento de datos) e Información (Productos).

## DEFINICIÓN DE UN SIG

![[Pasted image 20260911224140.png]]

## OPERACIONES ESPACIALES Y NO ESPACIALES

- Muchos programas de computación como, por ejemplo, Excel, o paquetes de dibujo como AutoCAD pueden manejar datos simples geográficos o espaciales, coordenadas (X,Y). Entonces, ¿por qué no son considerados como SIG?

- Un SIG es solamente un SIG si este permite realizar operaciones espaciales sobre los datos.

## CONSULTAS NO ESPACIALES

- No requiere almacenar valores de coordenadas como ser latitud y longitud o (x,y).
- No describe lugares que se relacionan con la ubicación geográfica.
- Ejemplos:

1. ¿Cuál es el número promedio de gente que trabaja con SIG en la ciudad de Santa Cruz?
2. Cuántos enfermos de dengue existen en cada departamento.

## CONSULTAS ESPACIALES

- Solamente son respondidas usando coordenadas (X,Y) o latitud y longitud.
- Solo un SIG puede responder este tipo de consultas.
- Ejemplos:

1. Cuánta gente trabaja en SIG en la parte norte de la ciudad de Santa Cruz.
2. Qué existe en una posición (X,Y).
3. Qué existe dentro de un manzano de una ciudad.
4. Qué líneas de micros pasan por una ubicación geográfica.

## UNIÓN DE DATOS

![[Pasted image 20260911224349.png]]

**Emparejado exacto**: es la unión de datos como en una base de datos relacional.

**Emparejado no exacto** se divide en dos:

- Emparejado jerárquico: donde la relación o unión de datos es por jerarquía de datos.
- Emparejado borroso: esta clase de unión de datos es la que utilizan los SIG.

## UNIÓN DE DATOS – EMPAREJADO BORROSO

Varias capas de datos relacionados pueden representar las muchas geografías del mundo real. Ver gráfico:

![[Pasted image 20260911224407.png]]

En el gráfico se pueden ver tres capas que representan el mundo real: Customers, Buildings y Streets.
En el emparejado borroso, el factor de relación entre las diversas capas de información espacial es la Referencia Geográfica, como en el gráfico; estas se relacionan mediante la línea roja que tiene una coordenada (x,y) en cada una de las capas.

## PREGUNTAS QUE UN SIG PUEDE RESPONDER

Al SIG se lo ha descrito de dos formas:

- A través de definiciones formales.
- A través de la habilidad de realizar operaciones espaciales, encadenando datos usando la localización como llave común.

Puede también distinguirse un SIG listando los tipos de preguntas que este puede ser capaz de responder.

Existen 5 preguntas genéricas que un SIG sofisticado puede responder.

## LOCALIZACIÓN O POSICIÓN GEOGRÁFICA

Las preguntas que puede responder un SIG en este tipo de preguntas son:

- Qué existe en una localización particular.
- Una localización puede ser descrita de muchas formas:
- Nombre del lugar.
- Código postal o teléfono.
- Referencia geográfica: latitud, longitud.

Ejemplo: qué existe en la localidad con código de área 3.

               Qué existe en la posición geográfica (200000,6700000).

## CONDICIÓN

Este tipo de preguntas necesita de una condición.

- Requiere de análisis espacial para responder, al contrario de la anterior.
- Esta pregunta necesita saber la localización que satisface ciertas condiciones.
- Ej.: una sección deforestada < 2000 m².

## TENDENCIA

Este tipo de preguntas:

- Involucra las dos primeras.
- Desea encontrar las diferencias dentro de un área con el tiempo.
- Se relaciona con el tiempo.

Ejemplo: cuál fue la trayectoria de un río específico en el año 1900.

## PATRONES

Este tipo de preguntas es más complicada:

- Pregunta más sofisticada.
- Cuántas anomalías existen que no se ajustan a los patrones y dónde están localizadas.
- Ejemplo: si el cáncer es una causa mayor de muerte entre residentes cercanos a una planta nuclear.

## MODELAMIENTO

Este tipo de preguntas es más para realizar simulaciones.

- Preguntas propuestas para determinar qué pasa si...
- Ejemplos:

Si un nuevo camino es adicionado a una red.

 Si una substancia tóxica se filtra a la red de agua local.

- Para responder este tipo de preguntas se requiere de datos geográficos, así como otra información descriptiva.

## RELACIÓN CON OTROS SISTEMAS DE INFORMACIÓN

LOS SIG SE RELACIONAN CON TODOS LOS SISTEMAS DE INFORMACIÓN, UTILIZANDO SUS CARACTERÍSTICAS, Y ESPECIALMENTE CON LOS SIGUIENTES SISTEMAS:

![[Pasted image 20260911224531.png]]

## CARTOGRAFÍA COMPUTARIZADA

**La Cartografía computarizada:**

Producen mapas con buena salida vectorial (formato); lo importante de estos sistemas es el despliegue de los datos.

No es importante el manejo y análisis de los datos geográficos.

## LOS DBMS

**DBMS**

Un DBMS trabaja sobre todo con datos no espaciales (alfanuméricos), incluyendo datos geográficos.

Tiene limitaciones al momento del despliegue gráfico y al realizar el análisis de tipo espacial.

Los SIG manejan sus tablas de datos no espaciales en un nivel básico.

## CAD Y AM/FM

**CAD y AM/FM**

(Automatic Mapping/Facility Management)

Los elementos básicos de datos de los CAD son: Line, Circles and Arcs, Lines, Symbols, Text y otros. Estos están referenciados a un sistema de coordenadas (GRILLA).

Los datos en un CAD están organizados en "Layers".

Ejemplos de esos sistemas son la representación de redes de agua, calles, electricidad, etc.

## RELACIÓN CON SISTEMAS REMOTOS

**Sistemas Remotos**

Se definen como la técnica de adquisición y procesamiento digital posterior de los datos de la superficie terrestre desde sensores instalados en plataformas espaciales (satélites, drones), en virtud de la interacción electromagnética existente entre la tierra y el sensor.

Como resultado de estos sistemas están las imágenes satelitales de diversos formatos (Hertz, Landsat, Ikonos, etc.).

En SIG esta información se denomina RASTER.

## APLICACIONES DE UN SIG

- **En Gobiernos**

- Planificación, zonificación, seguridad pública, valoración de tierras.

- **Administración de Recursos**

- Pesca y planificación de la fauna, agricultura.
- Manejo de recursos minerales y energéticos.

- **Actividades diarias**

- Electricidad, agua, gas, petróleo, telecomunicaciones, TV cable.

- **Demografía**

- Análisis de mercado, salud.

- **Educación**

- Universidades, laboratorios, bibliotecas, institutos de investigación.

**CONCLUSIÓN**: Un SIG es una herramienta de propósito general.

## COMPONENTES DE UN SIG

LOS COMPONENTES DE UN SIG SON: PRODUCTOS INFORMATIVOS, DATOS, SOFTWARE, HARDWARE, PROCEDIMIENTOS Y GENTE.

![[Pasted image 20260911224730.png]]

## PRODUCTOS INFORMATIVOS

- Es el resultado que se quiere obtener del SIG.
- Puede tomar la forma de mapas, informes, gráficos, listas, información digital que puede transmitirse o cualquier combinación de estos elementos.
- Lo importante es tener bien identificados estos productos con suficiente claridad para saber qué datos almacenar en las bases de datos.

## DATOS

- Es uno de los componentes más importantes de los SIG y los más difíciles de adquirir, pues se requiere de un largo y costoso proceso de adquisición.
- Al saber qué productos informativos debemos tener como resultados de los SIG, se puede planificar la adquisición de datos que se necesiten o que ya existan.
- Qué puede crear a partir de fuentes existentes.
- Qué grados de precisión y escala requerirá para los mapas.
- El formato de los datos es un factor para elegir el software SIG.

## SOFTWARE

- Los software proporcionan las funciones necesarias para realizar el análisis espacial y no espacial, almacenamiento y creación de los productos informativos que se desea.
- Este componente tiene dos procesos: ingreso de datos espaciales y codificación de atributos.
- El software SIG debe tener una interfaz gráfica de usuario para facilitar el acceso a las herramientas de análisis espacial.

## HARDWARE

- De acuerdo con los productos informativos que se desea elaborar o conseguir mediante un SIG, se debe necesitar los siguientes tipos de hardware:

- Servidores.
- Computadores.
- Plotters o impresoras de mapas.
- Scanners de dimensiones grandes.
- Red.
- Ancho de banda de conexión a internet.
- Otros.

## PROCEDIMIENTOS

- Un SIG debe operar de acuerdo con un PLAN (métodos) bien definido y a estándares de la empresa, las cuales son modelos y prácticas de operación únicas en cada organización.
- Se refieren a la manera como las personas realizan sus trabajos y los cambios que tendrán que adoptar para trabajar con un SIG.
- Plan de migración para facilitar la transición del método antiguo al nuevo.
- Tener en cuenta cómo los sistemas existentes coexistirán con el SIG.

## RECURSOS HUMANOS

- Requiere de un recurso humano adecuado y con conocimientos especializados para crear o usar el sistema.
- Sin el personal experto, la información se desactualiza y se maneja erróneamente.
- El hardware y el software no se manipula en todo su potencial.
- Entre los usuarios del SIG se encuentran especialistas técnicos, que diseñan y mantienen el sistema para los que se utilicen diariamente.
- Interviene mucha gente con diferentes especialidades como ser geógrafos, urbanistas, geólogos, de medio ambiente, informáticos y otros.

## CÓMO FUNCIONAN LOS SIG

- El Sistema de Información Geográfica almacena la información gráfica en capas temáticas que pueden enlazarse geográficamente.

- Cada capa se encuentra enlazada además con una o varias bases de datos, utilizando el concepto relacional para la consulta de los mismos.

- Las capas se relacionan con las tablas mediante un identificador.

![[Pasted image 20260911224830.png]]

![[Pasted image 20260911224939.png]]

# LAS TAREAS DE UN SIG

## INGRESO Y VERIFICACIÓN DE LA INFORMACIÓN

1.- Entrada de datos espaciales (construcción de base de datos geográfica).

- Este proceso de abstracción tiene diversos niveles, comienza con la concepción de la estructura de la base de datos, generalmente en capas.
- Existen cinco métodos básicos de entrada de datos espaciales:

- Coordenadas usando coordenadas geométricas.
- Conversión de información digital existente.
- Scanner.
- Digitalizador manual.
- Digitalización automática.

2.- Entrada de datos no espaciales.

- Ingreso de datos de atributos en archivos de texto a un motor de base de datos, previamente modelado y diseñado el modelo de datos descriptivo.

3.- Unión de datos espaciales y no espaciales.

- Se enlazan los datos espaciales con los datos alfanuméricos o de atributos o descriptivos.
- También se verifica la exactitud de la relación entre los datos espaciales y no espaciales.

## TRANSFORMACIÓN Y MANIPULACIÓN DE LA INFORMACIÓN

Engloba dos clases de operaciones:

- Transformación necesaria para corregir errores de la información, para actualizarla o para adecuarla a otro conjunto de información.
- Transformaciones que se deben realizar, según el método de análisis que se emplee para dar respuestas a las interrogantes previamente planteadas.

Estas transformaciones pueden operar en los aspectos espaciales y no espaciales de la información. Por separado o en conjunto.

**Ejemplos**: cambios de escala, cambios de proyecciones, recuperación lógica de la información, formatos, área y perímetros.

## INTEGRACIÓN Y MODELADO

- Los SIG integran la información existente de datos espaciales y no espaciales formando modelos que representan el mundo real.

- El modelado en los SIG se realiza sobreponiendo información espacial (superposición de mapas). Implica:

- Proceso geométrico.
- Topológico.
- Integración de capas de información.

- El producto es un mapa nuevo.

La superposición de mapas o modelado, además de ser una herramienta analítica, también es usada para una serie de procesos de manipulación.

## MANEJO Y ADMINISTRACIÓN

**§** En proyectos pequeños puede que sea posible almacenar la información geográfica como archivos simples.

**§** Sin embargo, llega un punto en el que el volumen de los datos aumenta; en esos casos es mejor la utilización de un sistema de administración de base de datos (DBMS).

## ANÁLISIS DE CONSULTAS

Los SIG pueden realizar el análisis de consultas espaciales y no espaciales.

**Recuperación y Presentación de la Información**

- Se refiere a la forma de extraer y mostrar los productos.

**a) Especificación Geométrica: (ver siguiente parte)**

- Se determina un área específica, de forma cualquiera, y se pide toda la información de esa área.
- De una determinada área se pide toda la información o ítems que cumplan una condición.
- Ejemplo: provincias de SCZ > de un valor.

**b) Especificación Descriptiva:**

- Se elige una base de datos referente a un área y se pide toda la información o atributos de los registros.
- De una base de datos elegida de un área se seleccionan aquellos registros que cumplan con determinadas condiciones.

## ANÁLISIS DE CONSULTAS (CONTINUACIÓN)

Existen operaciones espaciales como: unión, intersección, identidad, clip, erase, update.

Pero la más importante es BUFFER: consulta información dentro de un área puntual que genera un área de influencia circular, lineal y polígono. Así como se ve en la figura.

![[Pasted image 20260911225035.png]]

![[Pasted image 20260911225413.png]]

# LECCIÓN N.° 2

# INTRODUCCIÓN

En esta lección aprenderemos sobre:

1. Elementos básicos que debe tener un mapa en papel.

    - Objetos geográficos.
    - Descripción de los objetos.
    - Escala.
    - Sistema de coordenadas.

2. Uso de un computador para manejar mapas:

    - Información espacial.
    - Información descriptiva.

## CONCEPTO DE MAPA BASE

Un **Mapa Base** es el mapa principal donde se realizará todo el trabajo de SIG.

Un mapa muestra la siguiente información de los objetos o características geográficas:

1. **Información Espacial**

- Describe o muestra la localización o posición del objeto geográfico.
- Muestra la forma del objeto geográfico.
- Muestra la relación que existe entre objetos geográficos como, por ejemplo: qué está al lado derecho de un río, o qué objeto se encuentra dentro de otro objeto geográfico.

2. **Información Descriptiva**

- Es la información descriptiva de los objetos geográficos que se encuentran en el mapa.

Ejemplo:

Se muestra a continuación un mapa con su información espacial y descriptiva.

- **Información espacial**: la forma de los departamentos y la posición de los ríos.
- **Información descriptiva:** los nombres de los departamentos, nombres de los países que rodean Bolivia y el cuadro de referencias.

En los mapas existen también informaciones adicionales como ser título del mapa, escala del mapa, gráfico del norte geográfico y el reticulado del sistema de coordenadas.

![[Pasted image 20260911225514.png]]

## REPRESENTACIÓN DE OBJETOS GEOGRÁFICOS

Características u objetos geográficos son objetos localizados sobre o cerca de la superficie de la tierra.

Esos objetos geográficos pueden:

- **Ocurrir en forma natural**, donde no intervino la mano del hombre, como ser: montañas, lagos, volcanes, etc.
- **Ser construcciones**, donde intervino la mano del hombre, como ser: puentes, caminos, ciudades, aeropuertos, etc.
- **Ser subdivisiones de la tierra**, como ser: países, departamentos, provincias, etc.

## COMPONENTES DE LOS OBJETOS GEOGRÁFICOS

Los objetos o características geográficas tienen los siguientes componentes:

1. **Geometría**: que muestra la forma del objeto geográfico.
2. **Atributos**: muestra la descripción del objeto geográfico, como ser nombre del departamento.
3. **Comportamiento**: muestra la relación entre objetos geográficos, como ser: si una calle intersecta una manzana, si un río atraviesa un departamento.

![[Pasted image 20260911225733.png]]

# USO DE MAPAS PARA REPRESENTAR DATOS GEOGRÁFICOS

## CÓMO LOS MAPAS TRANSMITEN INFORMACIÓN GEOGRÁFICA

- Los mapas modelan el mundo real con puntos, líneas, áreas y superficies.

- También utilizan símbolos y etiquetas para hacer una descripción de los objetos geográficos mostrados en el mapa:

![[Pasted image 20260911225851.png]]

## CÓMO LOS MAPAS TRANSMITEN INFORMACIÓN DESCRIPTIVA

Los mapas transmiten información descriptiva de los objetos geográficos usando símbolos y etiquetas como ser:

- Caminos son dibujados con:

- varios anchos de línea,
- colores para representar diferentes clases de caminos.

- Ríos y lagos son dibujados usando color azul para representar agua.
- El uso de símbolos especiales denota características específicas de un objeto geográfico.
- Las calles son etiquetadas con nombres.
- Las construcciones especiales son etiquetadas con sus nombres.

En el gráfico mostrado se pueden observar los nombres de los departamentos y colores que diferencian a cada departamento; también se representan ríos de color azul, como también las fronteras de los departamentos con líneas segmentadas.

![[Pasted image 20260911225932.png]]

## CÓMO LOS MAPAS TRANSMITEN RELACIONES ESPACIALES

- En los mapas las relaciones espaciales son importantes.
- Ayudan a entender situaciones y realizar la toma de decisiones.
- La relación entre características u objetos geográficos se llama Relación Espacial.
- Las relaciones espaciales en un mapa son implícitas, por ejemplo:

- Qué característica geográfica **conecta** a otra.
- Cuál característica geográfica es **adyacente** a otra.
- Cuál característica geográfica **está contenida** en un área.
- Cuál característica geográfica **intercepta** a otra.
- Cuál característica geográfica **está cerca** de otra.

Ejemplo: qué avenidas **interceptan** el Segundo Anillo.

QUÉ RELACIÓN ESPACIAL CORRESPONDE A LA SIGUIENTE SITUACIÓN DE SANTA CRUZ Y BOLIVIA.

# CONCEPTOS ADICIONALES DE MAPAS

- La distancia es una parte importante de las relaciones entre características geográficas.
- A menudo se necesita conocer la distancia de un objeto a otro.
- Ej.: distancia entre un aeropuerto y un hotel.
- Para convertir una medida de mapa a distancia del mundo real, se debe conocer la escala del mapa.
- La Escala es la relación entre la distancia en un mapa y la distancia correspondiente en el mundo real. Ej.: 1:100000 (que significa que un cm en papel hace cien mil cm en el mundo real).
- La escala tiene efecto en la resolución y precisión del mapa.

A CONTINUACIÓN, EJEMPLOS DE LA VARIACIÓN DE LA ESCALA EN UN MAPA QUE AFECTA A LOS DOS EJES X e Y.

![[Pasted image 20260911210730.png|478]]

### CÁLCULO DE LA ESCALA DE UN MAPA

Calcularemos la escala de un mapa con los siguientes datos:

- Distancia en papel: Dp = 25 cm.
- Distancia en el mundo real: Dr = 50 km.

**DESARROLLO DEL CÁLCULO:**

- Según la definición: Escala = Dp / Dr.
- Escala: 25 cm / 5000000 cm.
- Dividir el numerador y el denominador entre 25 cm se tiene:
- Escala 1 / 200000 (resultado del cálculo).
- Notaciones:

- Escala Texto 1:200000.
- Escala Gráfica.

![[Pasted image 20260911210901.png|173]]

## EJEMPLO

![[Pasted image 20260911211312.png]]

# LECCIÓN N.° 3

## INTRODUCCIÓN A REPRESENTAR INFORMACIÓN GEOGRÁFICA

En los Sistemas de Información Geográfica existen tres modelos para representar información geográfica en un computador:

1. Modelo de datos vector (MDV).
2. Modelo de datos raster (MDR).
3. Modelo TIN (Triangulated Irregular Network).

En esta lección veremos el modelo vector y el modelo raster.

## MODELO DE DATOS VECTOR (MDV)

El MDV representa objetos o características geográficas en una computadora similares a la forma en que los mapas son hechos.
Utiliza: puntos, líneas y áreas.

Cada posición geográfica es registrada como una sola coordenada (x,y).

A continuación se muestra cómo se guardan las coordenadas como puntos, líneas y áreas:

- **Puntos**: es registrado como una sola coordenada (x,y).
- **Líneas**: son registrados como una serie de coordenadas (x,y).
- **Áreas**: son registrados como una serie de coordenadas (x,y) y definiendo segmentos que definen un área o polígono.

Esta lista de coordenadas representa cómo los objetos geográficos son almacenados en una computadora como un conjunto de coordenadas (x,y).

![[Pasted image 20260911212554.png]]

## MDV (CONTINUACIÓN)

Una lista de coordenadas para cada característica es asociada con el número de identificación.

![[Pasted image 20260911212914.png]]

## ESTRUCTURA DE DATOS ARCO-NODO

- Las fronteras comunes de dos parcelas o polígonos adyacentes no deben repetirse cuando se dibuja sobre un mapa.
- Esto se aplica para almacenar fronteras comunes en una computadora.
- Donde sea, se debe evitar la posible duplicación de datos.
- Repetir las coordenadas de un punto compartido por un número de líneas es ineficiente.
- Sería almacenado muchas veces.
- Entre polígonos adyacentes, almacenar cada polígono como una vuelta cerrada de coordenadas es también ineficiente.
- La manera más eficiente para almacenar datos vector es la estructura Arco-Nodo.
- La estructura de datos Arco-Nodo almacena y referencia datos tal que los nodos construyen arcos y los arcos construyen polígonos.
- Los nodos definen los dos puntos inicial y final de un arco.
- Los nodos pueden o no pueden conectar a dos o más arcos.
- Arco es el segmento de línea entre dos nodos.
- Un arco está compuesto de sus dos nodos y una serie ordenada de puntos los cuales definen su forma, vértices.

![[Pasted image 20260911213307.png]]

## TOPOLOGÍA

Es una rama de la matemática que estudia relaciones espaciales.

En SIG es una herramienta que permite mantener relaciones espaciales entre objetos geográficos.

De esta forma no habrá huecos entre fronteras, los arcos estarán conectados o las superficies no se solaparán.

La estructura de datos Arco-Nodo soporta tres conceptos:

- Conectividad: arcos conectan a cada uno de los nodos.
- Definición de área: arcos que conectan alrededor de un área definen un polígono.
- Contigüidad: los arcos tienen dirección y lados derecho e izquierdo.

## CONECTIVIDAD

- Un arco es definido por dos nodos finales: From-node y To-node.
- La topología arco-nodo es soportada a través de una lista arco-nodo.
- Permite identificar una ruta al aeropuerto o conectar arroyos con ríos.

![[Pasted image 20260911213712.png]]

## DEFINICIÓN DE ÁREA

- Muchos de los objetos que deseamos representar cubren un área sobre la superficie de la tierra. Ejemplos: lagos, etc.
- Un área es representada en el MDV por uno o más límites definiendo un polígono.
- La estructura de datos arco-nodo representa polígonos como una lista ordenada de arcos más que una figura cerrada de coordenadas x,y.
- Esto es denominado Topología Polígono-arco.

![[Pasted image 20260911213858.png]]

## CONTIGÜIDAD

- Dos objetos geográficos que comparten un límite son llamados adyacentes.
- La contigüidad permite al MDV determinar la adyacencia.
- El from-node y el to-node definen un arco.
- Esto indica la dirección de un arco para que puedan ser identificados los polígonos izquierdo y derecho.
- La topología Izquierdo-derecho se refiere a los polígonos del lado izquierdo y derecho de un arco.

![[Pasted image 20260911214335.png]]

## EXTENSIONES DEL MDV

- Otras asociaciones entre características geográficas son importantes para modelar:

**_"Una característica geográfica puede ser compuesta de otras características"_**

- Ej.: un estado, conjunto de ciudades; una ruta de bus puede ser una asociación de secciones de calles.

**_"La misma característica geográfica puede cambiar con el tiempo y un rastreo histórico de los cambios es importante"_**

- Ej.: una parcela es subdividida y la forma original y la información de atributos debe ser mantenida. El flujo de tráfico a lo largo de una ruta cambia en diferentes periodos de tiempo.

**_"Las características geográficas de la misma clase pueden sobreponerse"_**

- Ej.: aplicado al control de las especies, áreas de mercados de competencia, dos rutas de bus usan la misma sección de calle.

Existen dos extensiones en el MDV: Regiones y Rutas.

## REGIONES

- Las Regiones soportan el modelamiento de complejas relaciones entre polígonos.
- El bloque de construcción de un polígono es el arco y el bloque de construcción de una región es el polígono.
- Una región es representada por un conjunto de polígonos.
- Los polígonos en el MDV no se sobreponen y cubren completamente el área representada.
- En una región los polígonos pueden sobreponerse.

![[Pasted image 20260911215044.png]]

Una premisa de polígono es que cada objeto geográfico es representado por un polígono.

- Una sola característica u objeto geográfico puede ser representada por varios polígonos.
- Ej.: islas de Hawái.

![[Pasted image 20260911215051.png]]

- La construcción de regiones con polígonos es similar a la construcción de polígonos de arcos.
- Una región es una lista de polígonos.
- El orden de los polígonos no es significante.
- Como los polígonos comparten un arco, también las regiones comparten polígonos donde se sobreponen.

![[Pasted image 20260911215057.png]]

## RUTAS

- Define caminos a lo largo de un conjunto existente de objetos geográficos lineales.
- Las Rutas están basadas en arcos.

Ejemplo: definir una ruta desde un hotel hasta el aeropuerto sobre una red de caminos.

![[Pasted image 20260911215240.png]]

![[Pasted image 20260911215749.png]]

## INTRODUCCIÓN AL MDR

- El enfoque en el Modelo de Datos Raster (MDR) está en la localización.
- El MDR es más como una fotografía que un mapa.
- Una foto está hecha de una serie de _dots_ de diferentes colores.
- El MDR trabaja de la misma manera: usa una grilla regular de _dots, cells, pixels_ con valores.
- La imagen almacenada en computadora es usando el MDR.
- Existen 3 formas de interpretar una foto:

- **Clasificar** cada punto como perteneciente a algún grupo de similares características.
- **Medir** el valor de su color o sombra de grises.
- **Definir** el pixel relativo a un punto de referencia conocido. Ej.: bajo el nivel del mar.

![[Pasted image 20260911215846.png]]

- Estas tres interpretaciones pueden ser usadas en el MDR.
- El valor de la celda representa una clasificación, ejemplo: un tipo de vegetación.
- En el MDR, cada localización es representada como una celda.
- La matriz de celdas, que es organizada por filas y columnas, es llamada una grilla.
- Cada fila contiene un grupo de celdas con valores representando un fenómeno geográfico.
- Los valores de las celdas son números, representan datos nominales tales como clases de uso de suelos, intensidad de luz, calor, etc.

![[Pasted image 20260911215920.png]]

## REPRESENTACIÓN DE OBJETOS GEOGRÁFICOS EN MDR

- El MDR puede representar características u objetos geográficos discretos de puntos, líneas y áreas.

» Una característica punto es representada como un valor en una sola celda.

» Una característica lineal como una serie de celdas conectadas.

» Una característica de área como un grupo de celdas conectadas mostrando la forma.

![[Pasted image 20260911220938.png|439]]

![[Pasted image 20260911221048.png]]

# USANDO LOS MODELOS MDV Y MDR JUNTOS

## INTEGRACIÓN DE LOS MODELOS MDV Y MDR

- El MDV y el MDR son poderosas formas de modelar la tierra usando un computador.
- Cada uno usa el sistema de coordenadas cartesianas para definir localizaciones o posiciones.
- Adoptan una proyección de mapa, escalas y ajustan coordenadas compartiendo un origen común.

![[Pasted image 20260911221112.png]]

## COMPARACIÓN DE MODELOS ESPACIALES MDV Y MDR

![[Pasted image 20260911221144.png]]

## RASTERIZACIÓN Y VECTORIZACIÓN

- **RASTERIZACIÓN**: conversión de modelo vector a modelo raster.
- **VECTORIZACIÓN**: conversión del modelo raster a modelo vector.

![[Pasted image 20260911221257.png]]

# LECCIÓN 4.- REPRESENTANDO INFORMACIÓN DESCRIPTIVA EN UN COMPUTADOR

## INTRODUCCIÓN

En una lección anterior vimos que un mapa tiene dos tipos de información:

- **Espacial**: muestra los objetos geográficos.
- **Descriptiva**: hace una descripción de la información de los objetos geográficos.

En esta lección examinaremos los métodos disponibles para representar la información descriptiva acerca de los objetos o características geográficas.

También examinaremos cómo el dato descriptivo es organizado y cómo es encadenado al objeto geográfico en un modelo de datos espacial.

Los atributos o información descriptiva asociados con objetos geográficos son almacenados en el computador de una forma similar a como son almacenadas las coordenadas.

## TABLA DE ATRIBUTOS

En ArcGIS se almacena la información descriptiva en archivos .dbf. Estos archivos son conocidos como Tabla de Atributos.

También se pueden acceder a motores de bases de datos, como ORACLE, Informix, SYBASE, etc.

En la gráfica se puede observar que una capa de información geográfica puede conectarse simultáneamente con varias bases de datos.

![[Pasted image 20260911221415.png]]

## MODELO GEORRELACIONAL

- En mapas, los símbolos y textos comunican información descriptiva.
- Los mapas son herramientas poderosas para referenciar información.
- El modelo georrelacional es un concepto aplicado al modelo de datos espacial.
- El poder del SIG es capaz de encadenar el dato espacial y el dato tabular o descriptivo.
- Mantener la conexión entre las características u objetos geográficos y sus datos descriptivos es referido como un **Modelo de Datos Georrelacional**.

Próximo paso es entender cómo un LINK es creado entre la definición espacial de objetos geográficos y sus registros de atributos correspondientes. La respuesta es bastante simple:

- El único identificador de una característica asocia los atributos con las coordenadas de la característica.
- Mantiene una correspondencia de uno a uno entre los registros espaciales y los registros de atributos.
- El único identificador es almacenado físicamente en dos lugares:

- En los archivos conteniendo los X,Y.
- En la Tabla de atributos.

- Una vez hecha la conexión, se puede desplegar la información de atributos o crear un mapa basado en esos atributos, utilizando los procesos Relate o Links vs Join.
- Importante concepto relacional: Uno a muchos.

![[Pasted image 20260911223038.png]]

![[Pasted image 20260911221504.png]]

# LECCIÓN 5: ARCGIS

## INTRODUCCIÓN AL ARCGIS

- ArcGIS es un sistema que permite recopilar, organizar, administrar, analizar, compartir y distribuir información geográfica.
- ArcGIS es utilizada por personas de todo el mundo para poner el conocimiento geográfico al servicio de los sectores del gobierno, empresas, ciencia, educación y los medios.
- ArcGIS permite publicar la información geográfica para que esté accesible para cualquier usuario. El sistema está disponible en cualquier lugar a través de navegadores Web, dispositivos móviles como smartphones y equipos de escritorio.
- Se puede pensar en el sistema ArcGIS como en una infraestructura para elaborar mapas y poner la información geográfica a disposición de los usuarios dentro de un departamento, por toda una organización, entre varias organizaciones y comunidades de usuarios o en Internet, para cualquier usuario interesado en acceder a ella.

![[Pasted image 20260911223147.png]]

## QUÉ SE PUEDE HACER CON UN ARCGIS

**Crear, compartir y utilizar mapas inteligentes**

- ArcGIS permite crear una variedad de mapas, entre ellos, mapas Web accesibles en navegadores y dispositivos móviles, diseños de mapa impresos de gran formato, atlas, mapas integrados en aplicaciones, etc. Independientemente de cómo se publica, un mapa de ArcGIS es un mapa inteligente que muestra, integra y sintetiza capas de información geográfica y descriptiva de diversas fuentes.

**Compilar información geográfica**

- ArcGIS permite sintetizar datos de diversas fuentes en una misma vista geográfica unificada. Estas fuentes de datos incluyen información de bases de datos geográficas, datos tabulares de sistemas de administración de bases de datos (DBMS) y otros sistemas empresariales, archivos, hojas de cálculo, vídeos y fotos con geoetiquetas, KML, CAD Data, fuentes en directo de sensores, imágenes aéreas y de satélite, etc.

- Crear y administrar bases de datos geográficas.

- Las bases de datos geográficas son la piedra angular del trabajo SIG profesional. Una base de datos geográfica hace posible que la información geográfica se almacene en un formato estructurado que simplifica la administración, la actualización, la reutilización y el uso compartido de los datos.

**Resolver problemas con el análisis espacial**

- El objetivo que persigue es derivar nueva información de los datos existentes para permitir una mejor toma de decisiones.

**Crear aplicaciones basadas en mapas**

- Al crear aplicaciones en la Web, en equipos de escritorio, smartphones, dispositivos tablet y otros dispositivos móviles; los mapas, los datos, las herramientas se convierten en productos de información que cualquiera puede usar. Esto prácticamente permite poner los mapas y las funcionalidades al servicio de otras personas en una amplia variedad de situaciones.

**Dar a conocer y compartir información mediante la geografía y la visualización**

## ARCGIS DISPONIBLE

Los profesionales de SIG utilizan ArcGIS for Desktop y ArcGIS for Server para crear y compartir contenido enriquecido e información geográfica.

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

- El último producto comercializado por la empresa ESRI (Environmental Systems Research Institute) es el ArcGIS.
- Este nombre se usa tanto para designar al conjunto de aplicaciones SIG de esta empresa (ArcGIS System) como parte de sus productos (ArcGIS Desktop). El esquema que ofrece la compañía es el siguiente:

- SIG antiguos de esta compañía:

- **Arc/Info** (hasta la versión 7.x): lanzado en 1981, este SIG es famoso internacionalmente por su capacidad de manejo y análisis de mapas vectoriales. Hoy en día se comercializa como parte del producto ArcGIS con el nombre de Arc/Info Workstation (Arc/Info 8.x y siguientes).
- **ArcView**: (hasta la versión 3.x): lanzado en 1992, nació como SIG de visualización y consulta sin capacidades de análisis. Las versiones 3.x, sin embargo, ya disponían de módulos de análisis. Este SIG se convirtió en el número uno del mercado y es el que evolucionó en el ArcGIS moderno.
- ArcGIS nace en 2001 con la versión 8.1, como evolución natural de ArcView y, opcionalmente, incorporando Arc/Info con el apellido de Workstation. Complicando las cosas, la compañía ofrece tres versiones del mismo producto ArcGIS (Desktop):

## APLICACIONES COMUNES DEL ARCGIS

- ArcGIS, en cualquiera de sus modalidades, está integrado a su vez por tres aplicaciones comunes: ArcMap, ArcCatalog y ArcToolbox.
- **ArcMap** es la aplicación central de ArcGIS, permite realizar tareas con los mapas y sus datos relacionados: visualización, edición, búsquedas, análisis, gráficos y reportes.
- **ArcCatalog** ayuda a organizar y gestionar los archivos de datos e información SIG, por medio de herramientas de exploración, administración, previsualización de archivos y gestión de los metadatos.
- **ArcToolbox** contiene herramientas para el geoprocesamiento, esto es: análisis, gestión y conversión de formatos y proyecciones de los mapas.

![[Pasted image 20260911223306.png]]

## APLICACIONES ESPECIALIZADAS DEL ARCGIS

Existen también aplicaciones especializadas que pueden adicionarse al entorno ArcGIS, denominadas extensiones; las más importantes son: Spatial Analyst, 3D Analyst y Geostatistical Analyst.

- **Spatial Analyst**: es factible realizar operaciones de modelación y análisis sobre archivos gráficos de tipo raster.
- **3D Analyst**: permite visualizar y analizar superficies tridimensionales, creando perspectivas realistas a partir de modelos digitales de terreno (MDT).
- **Geostatistical Analyst**: puede generar, a partir de puntos georreferenciados, superficies continuas producto de un análisis estadístico de tipo descriptivo o predictivo de determinados fenómenos espaciales.

## INICIANDO ARCMAP

Para ejecutar el ArcMap usaremos la siguiente secuencia de menú desde Windows: Inicio > Todos los programas > ArcGIS > ArcMap.

![[Pasted image 20260911223505.png]]

- Aparece la ventana de la figura de abajo. Los archivos de ArcMap o documento de ArcMap tienen la extensión .mxd. Se puede crear un nuevo documento de ArcMap partiendo de cero, o utilizar una plantilla, o bien abrir un documento previamente creado.

![[Pasted image 20260911223515.png]]

- Para abrir un proyecto, ejecutar de la barra de menú la opción File/Abrir.

- Luego dirigirse a la carpeta donde se encuentra el proyecto y abrir.

![[Pasted image 20260911223527.png]]

- La interfaz que por defecto del ArcMap muestra lo siguiente:

![[Pasted image 20260911223537.png]]

Ejecutando propiedades de una capa activa del menú contextual.

![[Pasted image 20260911223544.png]]

# VISUALIZACIÓN DE DATOS GEOGRÁFICOS

## OBJETIVOS

Los objetivos de esta lección son:

1. Aprender el manejo de mapas.
2. Añadir capas temáticas.
3. Manejar la tabla de contenidos.
4. Extraer información de las capas.

## FORMATOS DE ALMACENAMIENTO EN ARCGIS

En ArcGIS existen dos formatos para almacenar información geográfica y sus atributos:

- Shapefile, y
- Geodatabase.

## SHAPEFILE

**_SHAPEFILE_**

Un **_Shapefile_** es un formato vectorial de almacenamiento digital donde se guarda la localización de los objetos geográficos y los atributos asociados a ellos. Las entidades geográficas de un _shapefile_ se pueden representar por medio de puntos, líneas o polígonos (áreas).

Un **_SHAPEFILE_** es generado por varios archivos. El número mínimo requerido es de tres y tienen las extensiones siguientes:

- .**shp**: es el archivo que almacena las entidades geométricas de los objetos.
- .**shx**: es el archivo que almacena el índice de las entidades geométricas.
- .**dbf**: es el archivo DBASE que almacena la información de los atributos de los objetos (tabla de datos).

Además de estos tres archivos requeridos, opcionalmente se pueden utilizar otros para mejorar el funcionamiento en las operaciones de consulta a la base de datos, información sobre la proyección cartográfica o almacenamiento de metadatos. Estos archivos son:

- .**sbn** y .**sbx**: almacena el índice espacial de las entidades.
- .**fbn** y .**fbx**: almacena el índice espacial de las entidades para los _shapefiles_ que son inalterables (solo lectura).
- .**ain** y .**aih**: almacena el índice de atributo de los campos activos en una tabla o el tema de la tabla de atributos.
- .**prj**: es el archivo que guarda la información referida a sistema de coordenadas.
- .**shp**.**xml**: almacena los metadatos del _shapefile_.

## GEODATABASE

**GEODATABASE**

- Una **_geodatabase_** de ArcGIS es una colección de datasets geográficos de varios tipos contenida en una carpeta de sistema de archivos común, una base de datos de Microsoft Access o una base de datos relacional multiusuario DBMS (por ejemplo Oracle, Microsoft SQL Server, PostgreSQL, Informix o IBM...).
- Una **_geodatabase_** es algo más que una colección de datasets; el término geodatabase tiene diversos significados en ArcGIS:
- La **_geodatabase_** es la estructura de datos nativa para ArcGIS y es el formato de datos principal que se utiliza para la edición y administración de datos.
- Las **_geodatabases_** son el almacenamiento físico de la información geográfica, que principalmente utiliza un sistema de administración de bases de datos (DBMS) o un sistema de archivos. Puede acceder y trabajar con esta instancia física del conjunto de datasets a través de ArcGIS o mediante un sistema de administración de bases de datos utilizando SQL.
- Las **_geodatabases_** cuentan con un modelo de información integral para representar y administrar información geográfica. Este modelo de información integral se implementa como una serie de tablas que almacenan clases de entidad, datasets ráster y atributos. Además, los objetos de datos SIG avanzados agregan comportamiento SIG, reglas para administrar la integridad espacial y herramientas para trabajar con diversas relaciones espaciales de las entidades, los rásteres y los atributos principales.
- Las **_geodatabases_** poseen un modelo de transacción para administrar flujos de trabajo de datos SIG.

## TIPOS DE GEODATABASE

- Existen dos tipos de **_GEODATABASES_**:

- **_multiuser geodatabases_**, están diseñadas para organizaciones medianas y grandes.
- **_single-user_** geodatabases, están diseñadas para usuarios individuales.

![[Pasted image 20260913211808.png]]

CUÁLES SON LOS ARCHIVOS QUE MÍNIMAMENTE DEBEN EXISTIR EN EL FORMATO SHAPEFILE.

.SHX ✅
.DBF ✅
.SHP ✅
.PRJ ❌

## ADICIÓN DE CAPAS EN ARCMAP

- Para adicionar capas temáticas al mapa debemos usar el icono Add Data.

![[Pasted image 20260913212011.png]]

## MANEJO DE TABLA DE CONTENIDOS

- Para hacer visible o no una capa, presionar el botón.

![[Pasted image 20260913212027.png]]

## DESPLEGAR TABLA

- Para desplegar la tabla de atributos de una capa, presionar el botón **_Open Attribute Table_** del menú contextual.

![[Pasted image 20260913212043.png]]

# ANÁLISIS ALFANUMÉRICO DIRECTO

## ANÁLISIS ALFANUMÉRICO: INTRODUCCIÓN

El análisis alfanumérico consiste en la obtención de información nueva a partir de los atributos de las entidades espaciales, disponibles en las tablas de las capas. Estos análisis incluyen consultas, resúmenes estadísticos, nuevos datos a partir de los ya existentes, etc. Las consultas se utilizan para extraer información de los datos geográficos, aprovechando tanto las capacidades gráficas como las capacidades de las bases de datos asociadas a la información geográfica que se puede integrar en un SIG.

**Tipos de consultas:**

- Directa: con el botón de información o con la herramienta de selección sobre algún elemento de la parte gráfica.
- Gráfica: aprovechando las cualidades topológicas de la información geográfica y la relación entre los puntos, líneas y polígonos de las distintas capas.
- En base de datos: mediante sentencias de consulta en formato SQL.

Es importante señalar la interrelación e interactividad que hay entre los datos espaciales y la base de datos. Todo lo que resulte seleccionado en la base de datos queda seleccionado en los datos espaciales y viceversa. Por tanto, nos podemos servir tanto de los datos espaciales como de la base de datos para realizar nuestras consultas.

Por lo general, las consultas implican una selección de elementos pertenecientes a una capa. En muchos SIG, una vez hecha la selección, las distintas operaciones de análisis que se realicen utilizando esta capa solo tendrán en cuenta la selección previa.

## CONSULTA DIRECTA

Las consultas directas son el método más sencillo de extraer información de los datos geográficos. Se usan los datos espaciales de una única capa y es posible establecer las capas sobre las que se puede ejecutar las herramientas de selección.

Se pueden realizar pidiendo información sobre alguna entidad espacial, apareciendo los datos de la base de datos asociados a esa entidad.

## CONSULTA DIRECTA: IDENTIFY

**Identify**:

![[Pasted image 20260913212300.png]]

Sobre algún elemento espacial, aparecen los datos de la base de datos asociados a ese elemento.

## CONSULTA DIRECTA: SELECT FEATURES BY

También se pueden realizar con las herramientas de selección.

![[Pasted image 20260913212317.png]]

Pinchando o realizando un recuadro, círculo, polígono, línea sobre los elementos espaciales. Abriendo la base de datos o la tabla de atributos se obtiene la información de los elementos en los registros de la tabla que han quedado seleccionados.

También se pueden realizar con las herramientas de selección. Posteriormente, abriendo la base de datos se obtiene la información de las entidades que hemos consultado.

**Select Features by:** esta herramienta le permite seleccionar uno o varios elementos a la vez de una capa. Cambiará de color indicando que está seleccionado.

![[Pasted image 20260913212330.png]]

Se pueden seleccionar varios elementos a la vez, haciendo un rectángulo, círculo, polígono, línea sobre los elementos a seleccionar o presionando la tecla mayúsculas y seleccionándolos uno por uno sin soltar dicha tecla. Se puede visualizar la selección en la tabla de atributos de la capa.

El resultado de la consulta se verá como el siguiente gráfico, donde los objetos geográficos seleccionados se ven con líneas de color celeste.

![[Pasted image 20260913212346.png]]

## CONSULTA DIRECTA: OPEN ATTRIBUTE TABLE

**OPEN ATTRIBUTE TABLE:** esta herramienta permite consultar los valores que contiene un tema en su tabla de atributos, así como modificarlos, ordenarlos, seleccionar registros, etc.

Aparece la tabla de atributos del tema seleccionado. Si uno o varios registros aparecen de diferente color es porque están seleccionados. Cada registro o fila representa un elemento geográfico del mapa (polígono, punto, línea).

![[Pasted image 20260913212401.png]]

![[Pasted image 20260913212405.png]]

Se pueden observar los registros seleccionados en la tabla de la capa Bolivia y mostrados de color celeste.

# ANÁLISIS ALFANUMÉRICO: CONSULTA A LA BASE DE DATOS

## CONSULTA A LA BASE DE DATOS

**Consultas en la base de datos**

De modo general, para realizar una consulta en una base de datos hay que emplear un lenguaje específico, pero los SIG suelen tener una interfaz diseñada expresamente para realizar las consultas de manera sencilla. Muchos SIG admiten y emplean el lenguaje estándar SQL (Structured Query Language) para la realización de las consultas. La notación en este caso es la siguiente:

```
select * from <tabla> where <condicion>
```

que se traduciría por "selecciona todos los registros de la tabla llamada `<tabla>` que cumplan la condición `<condicion>"`.

La condición es una expresión cuyo resultado es verdadero o falso. Las expresiones están formadas por campos, operadores y valores:

```
<campo> <operador> <valor>

area = 50 000
```

Así, cuando un registro presenta en el campo "area" un valor igual a 50 000, el resultado de la expresión es verdadero y el registro resultará seleccionado.

Los operadores para valores numéricos son: = ; <> ; < ; > ; <= ; >=

```
<campo> <> <valor>
```

Resultará verdadero cuando el valor del campo sea distinto a `<valor>`.

Cuando se comparan cadenas de texto, los valores se ponen con comillas y los operadores son: = ; <> ; like. El operador like realiza una comparación usando caracteres comodín. El carácter "_" representa cualquier letra o número y el carácter "%" representa cualquier conjunto de números o caracteres.

```
<campo> like 'pin_'
```

Resultará verdadero para valores como 'pino' o 'pini'.

```
<campo> like 'pin%'
```

Resultará verdadero para los valores anteriores y otros como 'pinus', 'pinea' o 'pinicola'.

El operador Not (no) devuelve lo contrario: si verdadero, falso; si falso, verdadero.

Además, se pueden concatenar condiciones en una misma expresión usando operadores de conjuntos (booleanos) y paréntesis para asegurar la correcta evaluación de la condición:

And (y): el resultado es verdadero si se cumplen las dos condiciones.

Or (o): el resultado es verdadero si se cumple al menos una de las dos condiciones.

El orden de chequeo de las condiciones es de izquierda a derecha; los paréntesis permiten modificar este orden:

```
area = 200 or area > 50 and area < 100

area = 200 or ( area > 50 and area < 100 )
```

En la primera expresión, un registro de área 200 no quedará seleccionado: V o F y F = V y F = F.

En la segunda sí: V o ( V y F ) = V o F = V.

Finalmente, la palabra NULL representa un valor vacío, sin especificar:

```
<campo> is NULL
```

Seleccionará los registros cuyo `<campo>` esté vacío, y, al contrario:

```
<campo> is not NULL
```

## SELECT BY ATTRIBUTES

En ArcGIS se accede al interfaz desde el menú principal Selection – Select By Attributes, o también pinchando sobre una capa – botón derecho – Open Attribute Table – Options – Select By Attributes. En ambos casos se abre el cuadro de diálogo siguiente:

![[Pasted image 20260913212735.png]]

![[Pasted image 20260913212740.png]]

El cuadro de diálogo pregunta:

- **Layer**: capa sobre la que se quiere realizar la consulta.
- **Method**: crear una selección, seleccionar sobre lo ya seleccionado…
- Campos para realizar la selección; en este recuadro aparecen todos los campos de la tabla.
- **Get Unique values**: recuadro de la derecha donde aparecen los registros del campo seleccionado.
- **Select from:** recuadro para escribir las condiciones buscadas. Para los atributos numéricos las expresiones pueden incluir constantes, funciones o valores de otros campos de la tabla. Para atributos de texto las expresiones pueden incluir caracteres de texto que se escriben o de otros campos.

Los operadores lógicos que aparecen son los siguientes, permitiéndose la combinación de varios de ellos en una misma selección.

## EJERCICIO 1

REALIZAR LA SIGUIENTE CONSULTA:

MOSTRAR LA INFORMACIÓN DE LA CATEGORÍA A LA QUE PERTENECE EL ÁREA PROTEGIDA "ISIBORO SECURE".

USAR LA CAPA TEMÁTICA "ÁREAS PROTEGIDAS" Y LA COLUMNA "CATEGORIA" PARA OBTENER LA INFORMACIÓN REQUERIDA O EL RESULTADO DE LA CONSULTA.

PARA LA CONDICIÓN USAR LA COLUMNA "NOMBRE_AP" DE LA CAPA TEMÁTICA "ÁREAS PROTEGIDAS" (NOMBRE_AP = "ISIBORO SECURE").

SOLUCIÓN:

**RESPUESTA: Parque Nacional y Territorio Indígena**

**VIDEO DE LA SOLUCIÓN**

## EJERCICIO 2

REALIZAR LA SIGUIENTE CONSULTA:

SELECCIONAR LAS POBLACIONES QUE SON CAPITAL DE DEPARTAMENTO Y QUE TIENEN NÚMERO DE HABITANTES MAYOR A 100000.

PARA ESTA CONSULTA, USAR LA CAPA TEMÁTICA "POBLACIÓN".

PARA LA CONDICIÓN "CAPITAL DE DEPARTAMENTO" USAR LA COLUMNA "tipo_pobla" (tipo_pobla = "Capital De Departamento").

Y PARA OBTENER LA CANTIDAD DE HABITANTES USAR LA COLUMNA "poblacion_" EN LA CONDICIÓN (poblacion_ >= 100000).

RESPUESTA

![[Pasted image 20260913212814.png]]

VIDEO SOLUCIÓN DEL EJERCICIO

## CONSULTA ESPACIAL (LOCATION)

Las consultas espaciales son métodos de selección por atributos y características de la información geográfica basados en criterios espaciales, como ser: intersecciones, cruces, pertenencia, contenidas y otros.

En este tipo de consultas se van a usar las características espaciales de una capa para seleccionar los elementos geográficos de otra capa que cumplen unas condiciones.

Este tipo de consultas en ArcGIS se llaman _Select By Location_ dentro del menú _Selection_.

![[Pasted image 20260913212957.png]]

Descripción de las opciones:

**_Selection Method_**: tiene las siguientes opciones:

- **_Select Features From:_** selecciona objetos geográficos de.
- **_Add to the currently selected feature in_**: adiciona objetos a los actuales objetos seleccionados en.
- **_Remove from the currently selected feature in_**: remover objetos de los actuales objetos seleccionados en.
- **_Select from the currently selected feature in_**: selecciona objetos de los actuales objetos seleccionados en.

**_Spatial selection Method:_** tiene las siguientes opciones:

- **_Intersect_**: selecciona los elementos que son interceptados por lo seleccionado.
- **_Are within a distance of_**: selecciona los elementos que están a una distancia menor de lo que está seleccionado.
- **_Completely contain_**: selecciona polígonos que contienen completamente las entidades señaladas.
- **_Are completely within_**: selecciona los elementos que están completamente dentro de un polígono.
- **_Have their center in_**: selecciona elementos que tienen su centro o centroide dentro de las entidades señaladas.
- **_Share a line segment_**: selecciona líneas y polígonos (no vale para puntos) que comparten segmentos con los seleccionados.
- **_Touch the boundary of_**: selecciona líneas y polígonos (no vale para puntos) que tocan los límites de los elementos seleccionados (no cruzan).
- **_Are identical to_**: selecciona los elementos idénticos a los que están seleccionados.
- **_Are crossed by the outline of_**: (≈ intersect) selecciona elementos que tocan el límite de lo seleccionado (no para puntos). Se diferencia de intersect en que, por ejemplo, no selecciona líneas dentro de un polígono que no toquen el límite; intersect sí lo hace.
- **_Contain_**: (≈ completely contain) selecciona elementos (continente) que contienen todo o parte de las entidades señaladas (diferencia con completely contain). Incluye también a los que tocan el borde.
- **_Are contained by_**: (≈ are completely within) selecciona los elementos que están dentro, todo o en parte, (contenido) de un polígono (continente). (Diferencia con are completely within). Incluye también a los que tocan el borde.

## EJERCICIO 1 DE CONSULTA ESPACIAL

Calcular cuántas poblaciones existen dentro del área protegida "Isiboro Secure".

Usar los siguientes Shapes:

1. Bolivia.
2. Áreas Protegidas.
3. Poblaciones.

SOLUCIÓN: 121 poblaciones.

**VIDEO DE LA SOLUCIÓN DEL EJERCICIO**

## EJERCICIO 2 DE CONSULTA ESPACIAL

Calcular cuántas poblaciones existen dentro del área protegida "Isiboro Secure"

y a la vez deben estar ubicadas en el departamento de Cochabamba.

Usar los siguientes Shapes:

1. Bolivia.
2. Áreas Protegidas.
3. Poblaciones.

**SOLUCIÓN: 89 poblaciones.**

**VIDEO DE LA SOLUCIÓN DEL EJERCICIO**

## EJERCICIO 3: CONSULTA ESPACIAL

Indicar qué poblaciones se encuentran a 100 metros del río "RIO PIRAY"; para esta consulta usar la columna NMA para identificar el nombre del río.

Usar los siguientes Shapes:

Shapes:

1. Bolivia.
2. Ríos Principales.
3. Poblaciones.

**SOLUCIÓN:**

**1. SINDICATO AGRARIO ILLIMANI A**

**2. COMUNIDAD AGUA HEDIONDA**

**VIDEO DE LA SOLUCIÓN DEL EJERCICIO**