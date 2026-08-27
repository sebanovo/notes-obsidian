
# 2026-05-08 Funcionalidades parte 1
Estos puntos si o si tenemos que tenerlos

### Funcionalidades generales
1.  Solución universal en su contexto basado en un modelo SaaS (Software as a Service), pueden distinguir tenants usando planes, empezar con el plan Básico solicitar tarjeta o forma de pago (Al defender explicar porque escogimos esta solución)
	- Colocar la app movil en la web (Boton de descargar App Mobile)
	- Cliente solo paga por suscripción y solo paga por lo que usa
2. Gestión de usuarios
	- Usuarios de toda índole nada fijo
	- Asignación de privilegios
	- Roles y permisos de toda índole nada fijo
	- Podríamos tener 3 categorías de usuarios a nivel de desarrollo 
		1. Tipo de usuario super Admin  solo nosotros como desarrolladores
		2. Admin del cliente (definir roles y usuarios)
		3. Tercer nivel indefinido (gran cantidad de roles que crea el Admin del cliente) 
	- Asignar privilegios sobre los roles (esconder elementos en la UI)
	- Asignar privilegios sobre los datos (esconder elementos  en la UI)
3.  Logs/Bitácora
	- Sirve para la auditoria del sistema / saber que paso con el sistema  (caja negra del avión)
	- Necesitamos guardar, clientes, ip, laptop del cliente, fecha y hora.
	- Donde almacenar esta información?
			- `Opción1 :` Cifrado en otra base de datos
			- `Opción2: `Sistema de archivo serializado o binario nada más el software sepa donde esta ese archivo como leerlo como cargarlo

4.  Copias de respaldo y restauraciones basadas en políticas bien definidas
	- `Opción1 :` servicio de aws de todo
	- `Opción2 :` función de SQL nativa para hacer backup


### Tarea Próxima clase
Investigar como hacer restauraciones y respaldo en los 2 tipos de tipo tenant 
- Comparten base de datos
- Los que tienen esquema separado

# 2026-05-13 Funcionalidades parte 2
5. Reportes  - Ningún reporte debe ser lanzado sin antes haber lanzado las características de datos que queremos que salga en un reportes
	- Ejemplo: (Select * from clientes), pero solo mostrar por criterios (nombre, saldo, etc.).
	- Ejemplo: Mostrar las ventas hechas entre la `fecha1` hasta la `fecha2`
	- Debe tener los filtros que se están aplicando en la parte del encabezado se debe ver cuales son los criterios que se toman en cuenta para hacer dicho reporte
	1. Todos los reportes deben tener al menos 3 posibilidades de exportación: 
		1.  Para visualizarlo en la pantalla
		2. Generarlo en pdf
		3. Exportarlo en excel
	2. Reportes analíticos y gerencial
		- Analítico muestra todo el detalle completo (detalle más información)
		- Gerencial datos genéricos (como un resumen)
	3. Reportes tipos dinámico
		- Basados en QBE (Consultas con ejemplo)
		- Yo entrego un ejemplo y el software genera la consulta y lo aplica al sistema
		- La idea es que el cliente coloque un ejemplo, va marcar que atributos debe tener los reportes, y en un Edit que criterios debe tener (ejemplo: profesión), talvez ordenado, talvez agrupado y genera el reporte de manera dinámico.
6. Generar Dashboards de acuerdo al tipo de proyecto (Análisis de datos)
7. Tecnología apropiada al público, define 3 modelos:
	- Procesos de software 
	- Métodos 
	- Herramientas
	1. BACKEND (SPRING-BOOT) como core  + FastAPI como segundo Backend
	2. FRONTEND (ANGULAR)
	3. MOBILE (FLUTTER), implementar: 
		- Notificaciones PUSH
		- Sensores (sensores de algún tipo)
		- GPS (coordenadas de geolocalización)
		- `Alternativas` : Micrófono, Cámara, etc.
		- Lectores de código de barra, puntos de ventas, balance digitales, registro de biométrico facial

### Fecha de presentación Sprint 2: Viernes 22 de mayo
### Fecha de presentación estás características: Lunes 1 de junio