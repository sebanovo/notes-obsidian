Aquí tienes la transcripción de la clase, revisada, limpia de muletillas y organizada de forma lógica y estructurada para que sea clara y fácil de estudiar:

---

# Proyecto Final de Grado: Sistema de Información Geográfica (SIG) Universitario

---

## 1. Introducción y Justificación del Proyecto

El objetivo principal es desarrollar una **herramienta de ayuda geográfica en entorno web** destinada a docentes, estudiantes y visitantes de la universidad.

### Problema / Necesidad

* **Orientación y consultas:** Un visitante o estudiante nuevo necesita saber rápidamente dónde quedan las facultades, los módulos, las oficinas administrativas o servicios de emergencia (como un consultorio o centro médico).
* **Solución propuesta:** Reemplazar las consultas verbales directas por una aplicación web interactiva que despliegue un **plano geográfico digital** con información alfanumérica detallada.

> **Alcance Geográfico:**
> * **Obligatorio:** El Campus Universitario, los Módulos y la zona de El Vallecito.
> * **Plus (Puntos extra):** Se valora la inclusión de facultades o sedes provinciales externas (ej. Vallegrande, Camiri, Montero).

---

## 2. Requerimientos del Sistema y Arquitectura

El proyecto consta de dos componentes o actividades principales:

```
                  ┌───────────────────────────────────────────┐
                  │           PROYECTO FINAL SIG              │
                  └─────────────────────┬─────────────────────┘
                                        │
             ┌──────────────────────────┴──────────────────────────┐
             ▼                                                     ▼
┌─────────────────────────┐                               ┌─────────────────┐
│ 1. Plano Geográfico     │                               │ 2. Aplicación   │
│    (Captura de Datos)   │                               │    Web + BD     │
└────────────┬────────────┘                               └────────┬────────┘
             │                                                     │
             ├─ Sistema de Referencia: WGS84                       ├─ Base de Datos Alfanumérica
             └─ Capas Vectoriales (Punto, Línea, Polígono)         └─ Módulo de Consultas Espaciales

```

### A. Elaboración del Plano Geográfico

1. **Sistema de Referencia:** Todos los datos geográficos deben estar estrictamente referenciados en **WGS84**.
2. **Tipos de Datos Vectoriales:**
* **Puntos:** Entradas, extintores, facultades/oficinas (si se representan de forma puntual).
* **Líneas:** Vías internas, caminos de circulación, rutas de navegación.
* **Polígonos:** Edificios, canchas deportivas, jardines, áreas verdes.


3. **Exactitud:** No se exige precisión milimétrica (un margen de error de $1\text{ m}$ o $2\text{ m}$ es aceptable siempre que el objeto se sitúe dentro de su área real).

### B. Desarrollo de la Aplicación Web

1. **Plataforma:** Debe ser una **Aplicación Web** conectada a una base de datos alfanumérica y espacial.
2. **Tecnologías / Frameworks:** Los grupos pueden acordar usar un framework o lenguaje común para facilitar la colaboración, aunque hay libertad de elección.
3. **Funcionalidades Mínimas:**
* Digitalización y visualización de capas geográficas.
* Edición y consulta de atributos en la base de datos.
* Cálculo de superficies/áreas de polígonos.
* Consultas espaciales interactivas (ej. seleccionar un punto y desplegar datos en texto e indicar su posición exacta en el mapa).



---

## 3. Asignación de Capas por Grupo

El sistema completo contempla un mínimo de **22 capas geográficas**. A continuación se detalla la distribución efectuada en clase:

| Grupo N° | Capa Asignada | Descripción / Alcance |
| --- | --- | --- |
| **G1** | **8. Escuelas de Posgrado** | Ubicación y datos de las escuelas de posgrado. |
| **G2** | **17. Kioscos y Fotocopiadoras** | Puntos comerciales y de servicio rápido. |
| **G3** | **2. Oficinas del Rectorado** | Distribución de oficinas administrativas del rectorado. |
| **G4** | **13. Detic y CPDs Facultativos** | Direcciones de TIC y centros de cómputo. |
| **G5** | **18. Campos Deportivos** | Canchas y recintos deportivos (Polígonos). |
| **G6** | **15. Bibliotecas** | Bibliotecas centrales y facultativas. |
| **G7** | **12. Oficinas de Extensión e Investigación** | Centros e institutos de investigación por facultad. |
| **G8** | **20. Parqueos y Sanitarios** | Áreas de estacionamiento y baños públicos. |
| **G9** | **22. Opciones de Navegación / Rutas** | Ruta de punto A a punto B o trazado de retorno (ej. invidentes). |
| **G10** | **19. Comedores y Lugares de Comida** | Puntos de venta de alimentos y comedores universitarios. |
| **G11** | **21. Escaneo / Realidad Aumentada** | Consulta de información apuntando desde el celular a un edificio. |
| **G12** | **9. Decanatos y Vicedecanatos** | Ubicación de autoridades facultativas. |
| **G13** | *(Sin representante presente)* | Pendiente de asignación. |
| **G14** | **5. Oficinas del Vicerrectorado** | Unidades administrativas dependientes del vicerrectorado. |
| **G15** | **10. Direcciones de Carrera** | Oficinas de atención de carreras universitarias. |
| **G16** | **4. Oficinas del Vicerrectorado (Complementaria)** | Mapeo coordinado con el grupo asignado a vicerrectorado. |
| **G17** | **16. Puntos de Interés Externo / Especiales** | Corte Electoral, Defensoría universitaria, etc. |
| **G18** | **7. FUP y Asociaciones Docentes** | Federación Universitaria de Profesores y sedes gremiales. |
| **G19** | **6. Órganos Especiales** | Defensoría, Tribunal Electoral Universitario, entre otros. |
| **G20** | **14. Laboratorios** | Laboratorios de computación, física, química, etc. |
| **G21** | **1. Oficinas Administrativas Principales** | Edificios administrativos generales. |
| **G22** | **11. Oficinas de Acreditación** | Unidades de evaluación y acreditación académica. |

---

## 4. Entregables y Productos Finales

Al finalizar el semestre se debe presentar:

1. **Plano Digital Universitario Integrado:** Un mapa unificado con todas las capas activas (facultades, centros, kioscos, laboratorios, etc.).
2. **Mapa con Leyendas Estándar:** Cuadro de referencias visuales (ej. Puntos azules = Facultades, Puntos rojos = Investigación).
3. **Tablas de Infraestructura y Base de Datos:** Estructura de base de datos relacional/espacial completa y poblada.
4. **Aplicación Web Funcional:** Sistema interactivo que ejecute las consultas alfanuméricas y espaciales.

---

## 5. Fechas e Indicaciones Administrativas

* **Conformación de Grupos:** Grupos de hasta **5 integrantes** (los grupos con 3 personas deben incorporar 1 o 2 miembros adicionales).
* **Fecha de Entrega Final:** Semana de exámenes finales (aproximadamente entre fines de noviembre y principios de diciembre).
* **Proyección Institucional:** Los mejores proyectos coordinarán con Decanato para presentar la herramienta a las autoridades universitarias (Vicerrectorado/DETIC) y publicarla oficialmente en el portal web institucional con el reconocimiento de autoría correspondiente a los estudiantes.