
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
- `Preguntas Diagno`

---
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
# Electrónica Industrial