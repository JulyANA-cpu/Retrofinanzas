RETROFINANZAS — PROTOTIPO LOCAL

Contenido: index.html, aplicación web móvil de demostración.

Cómo abrir:
- En computadora: abre index.html en un navegador moderno.
- Para usarla desde el teléfono mediante un enlace permanente, debe publicarse en un servicio de hosting HTTPS. Este paquete por sí solo no crea una URL pública.

Funciones incluidas:
- Resumen de ingresos de trabajos, costos de máquina y gastos personales.
- Registro de gastos, trabajos por hora/jornada/contrato y mantenimientos.
- Exportación CSV y respaldo/restauración JSON.
- Persistencia local en el navegador del dispositivo.

Limitaciones importantes:
- No tiene backend ni base de datos en servidor.
- No está conectada a Hotmail/Outlook, Banco Pichincha ni SRI.
- No realiza OAuth ni importa automáticamente facturas o movimientos bancarios.
- El almacenamiento local puede borrarse al limpiar datos del navegador y no sincroniza entre dispositivos.
- No usar como sistema contable definitivo ni introducir información altamente sensible.

Para producción se requiere hosting HTTPS, backend, base de datos, autenticación, integración Microsoft OAuth/Graph con permisos mínimos, carga y extracción segura de XML/PDF, importación bancaria y pruebas.
