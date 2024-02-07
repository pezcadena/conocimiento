> [!info]
> Todos los componentes se conectaran al ``state`` principal para evitar el uso de ``inputs``.

# Todos
## Recepción
- (Nuevo) Información básica del folio.
	- Garantía (No en servicio).
	- Verificación (Si hay verificación).
	- Moto (Si hay moto).
- (Nuevo) Información de la herramienta (o backup).
- (Nuevo) Información de la ubicación.
- (Nuevo) Observaciones.
	- Accesorios (No es servicio).
## Recepción Formulario
- (Nuevo) Formulario básico del folio.
- (Nuevo) Formulario de la herramienta (o backup).
	- Centro Costo (Par-Torque).
	- Backup (Par-Torque).
	- Torque (Part-Torque).
- (Nuevo) Formulario de la ubicación.
	- Línea, Operación, Husillo (Par-Torque).
- (Nuevo) Formulario de las observaciones.
	- Accesorios (No es servicio).
---
## Inspección
- `BackToBotton`.
- `DetallesFolio` (refactorizar).
- `ChecklistDisplay.`
- `Comments`.
## Inspección Formulario
- `BackToBotton`.
- (Nuevo) Formulario de fechas del proceso.
- `Checklist`.
- `Comments`.
---
## Diagnóstico
- `BackToBotton`.
- `DetallesFolio` (refactorizar).
- `ChecklistDisplay.`
	- MFU (Par-Torque)
- (Nuevo) Preguntas del diagnóstico.
- (Nuevo) Pruebas del diagnóstico.
- `Comments`.
## Diagnóstico Formulario
- `BackToBotton`.
- (Nuevo) Formulario de fechas del proceso.
- `Checklist`.
- (Nuevo) Componente del campo del MFU.
- `PreguntasDiagnostico`.
- `PruebasDiagnostico`.
- `Comments`.
---
## Refacciones
> [!info]
> Este proceso como tal no tendría una versión "formulario" porque el componente `RefaccionesModulo` se encarga de manejar cada refacción de manera individual.
- `BackToBotton`.
- (Nuevo) Componente de los mensajes de información al usuario.
- `RefaccionesModulo`
---
## Reparación (Servicio)
- `BackToBotton`.
- `DetallesFolio` (refactorizar).
- (Nuevo) Información de las fallas. (En servicio no se muestra)
- `Comments`.
## Reparación Formulario (Servicio Formulario)
- `BackToBotton`.
- (Nuevo) Formulario de fechas del proceso.
- (Nuevo) Formulario de las fallas (En servicio no se muestra).
	- (Nuevo) Incluye componente del modal de la falla.
- `Comments`.
---
## Entrega Interna
- `BackToBotton`.
- (Nuevo) Información de la entrega interna.
- (Nuevo) Modal del formulario para finalizar el folio.
	- Costo de mano de obra (No Par-Torque)
	- (Nuevo) Componente del campo para subir el certificado de verificación (No batería ni barra).
	- Fecha verificación (Solo verificaciones).
# Par-Torque
## Recepción
- ``RecepcionVerificacionCard``.
## Recepción Formulario
- (Nuevo) Formulario del historial especifico de la verificación.
---
## Inspección
- `FolioGaleriaFotos`.
## Inspección Formulario
- `FotosField`.
---
## Diagnóstico
- `FolioGaleriaFotos`.
## Diagnóstico Formulario
- `FotosField`.
---
## Reparación
- `FolioGaleriaFotos`.
## Reparación Formulario
- `FotosField`.
# Electrónica Industrial
## Diagnóstico Formulario
- (Nuevo) Modal para elegir el proceso siguiente.
--- 
## Reparación Externa
- (Nuevo) Información del archivo.
## Reparación Externa Formulario
- (Nuevo) Componente del campo para subir un archivo.
- (Nuevo) Componente del campo del comentario del archivo.