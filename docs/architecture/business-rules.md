# Reglas de negocio — SupplyTrack

## Registro de solicitudes

| ID | Regla de negocio |
|---|---|
| RN01 | El código de sucursal debe ser una cadena no vacía. |
| RN02 | El código del producto debe ser una cadena no vacía. |
| RN03 | La cantidad solicitada debe ser un número entero mayor a cero. |
| RN04 | El identificador del solicitante no debe estar vacío. |
| RN05 | Una misma solicitud no debe registrarse más de una vez. |
| RN06 | Toda solicitud nueva comienza con estado PENDING. |
| RN07 | Las solicitudes válidas deben enviarse a la cola de auditoría. |
| RN08 | Las solicitudes inválidas deben enviarse a la cola de errores. |