
### Primer Examen Parcial
Conecta a la gente que necesita un taller más cerca
Problemas a resolver cuando una persona tiene un vehículo con problemas,
Problemas por la cual usaría la app:
- Coche sin aire
- No enciende en la mañana
- Se choco
- Chapería
- Aire
- Caja mecánica/automática averiada

La persona entra a la app y se identificara (email + password), puede escribir, agregar fotografías, ubicación. La app usando la IA, analiza todo lo previo y hará la recomendación y les enviara una notificación y si la acepta el taller enviara una notificación al cliente.
La IA hará la recomendación por: 
- Distantica
-  Sugerencia de costos (como cajeros de binance)
- Rutas Criticas
- Por calificaciones de estrellas ⭐

Stack tecnológico
- Backend: Python (Fastapi)
- Frontend: Angular
- Data base: PostgreSQL
- Mobile: Flutter
- Deploy: AWS o Azure

Recomendable implementar
* Agregar Reportes
* Formas de pago Qr
* Sistema de seguro
	* Llantas pinchadas
	* Vidrio Roto 
	* etc.


### Preguntas del examen
1. La app esta completamente terminada en un 100% de acuerdo a lo solicitado?
2. La aplicación cuando un cliente en emergencia envía un audio, permite automáticamente analizando dicho audio identificar el tipo de emergencia que tiene el cliente y así mismo envía solicitudes a los talleres según el tipo de emergencia?
3. La aplicación envía notificaciones tipo push a través de la aplicación móvil de forma automática al cliente cuando se le asigna  un taller  y también notificaciones tipo push  a los talleres cuando hay alguna emergencia  en proceso?
4. La aplicación permite tomar una foto del vehículo en problemas y/o a partir de esa imagen determina e identifica el tipo de problema (problema del motor, choque frontal, falta de aceite, etc.)?
5. La documentación esta completa en un 100% de acuerdo al proceso unificado UML2.5?


# Segundo Examen Parcial
- Usar PUDS ciclo #2
- Primer ciclo primera versión operativa
- Segundo ciclo segunda versión operativa

### Requisitos
1. WebSockets
2. Ver en el mapa el recorrido en tiempo real (tipo Uber)
3. Lo anterior tanto en Mobile como en web
4. 100% Multitenant
5. Asignación mediante audio o texto(adjuntar imágenes) a que talleres generar invitación pero no a todos dependiendo de la distancia, o especialización. Cada taller acepta o no, Response (si o no).
6. Gran cantidad de métricas basadas en KPI:
	1. Tiempo promedio de asignación
	2. Tiempo promedio de llegada
	3. Tipo de incidentes o solicitudes
	4. Talleres más eficientes
	5. Zonas con más incidencias
	6. Casos cancelados (Atendidos o cancelados y cliente)
	7. Servicios atendidos dentro del tiempo esperado

7. Reportes dinámicos a partir de Promps  (Talleres  o SuperAdmin)
- Recomendación
- Convertir en SQL o consulta.
1. Funcionar app Mobile incluso en modo offline. (Estado de espera, recuperación hace de todo)
2. Funcionar app web igual que el 8. usando PWA


### Fecha de entrega 12 de junio
