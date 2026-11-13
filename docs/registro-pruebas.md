# Registro de pruebas - DulceReserva

Este documento recoge las pruebas funcionales previstas para comprobar que DulceReserva cumple sus requisitos principales.

Las pruebas se realizarán durante el desarrollo y la fase de comprobación de la aplicación. Actualmente todas se encuentran pendientes de ejecución.

## 1. Casos de prueba previstos

| ID | Requisito | Acción que se realizará | Resultado esperado | Estado |
|---|---|---|---|---|
| P01 | R03 - Registro de encargos | Crear un encargo con todos los datos obligatorios | El encargo se guarda y puede consultarse correctamente | Pendiente |
| P02 | R04 - Validación de formularios | Intentar registrar un encargo sin nombre del cliente o con otros campos obligatorios vacíos | Se muestra un mensaje de error y no se guarda el encargo | Pendiente |
| P03 | R05 - Disponibilidad y capacidad | Registrar un encargo que supere la capacidad configurada para una franja horaria | Se muestra una advertencia de sobrecarga antes de confirmar | Pendiente |
| P04 | R02 - Permisos de usuarios | Acceder como obrador e intentar modificar los datos de un encargo | El sistema impide la modificación de los datos del encargo | Pendiente |
| P05 | R08 y R10 - Previsión de producción | Registrar varios encargos, cancelar uno y consultar los totales de producción | La previsión muestra las cantidades correctas y excluye el encargo cancelado | Pendiente |

## 2. Procedimiento de ejecución

Para realizar cada prueba se seguirá este procedimiento:

1. Preparar los datos necesarios utilizando información ficticia.
2. Ejecutar la acción indicada en el caso de prueba.
3. Comparar el resultado obtenido con el resultado esperado.
4. Registrar el resultado real, la fecha y las observaciones.
5. Guardar una captura u otra evidencia cuando sea necesario.
6. Si la prueba falla, crear una incidencia en GitHub Issues y repetirla después de corregir el problema.

## 3. Plantilla para registrar una prueba

- **Identificador:** P__
- **Fecha:** Pendiente
- **Requisito relacionado:**
- **Acción realizada:**
- **Resultado esperado:**
- **Resultado obtenido:**
- **Estado:** Pendiente / Superada / Fallida
- **Evidencia:**
- **Observaciones:**
- **Incidencia relacionada (si existe):**

## 4. Registro de resultados

| ID | Fecha | Resultado obtenido | Estado | Evidencia | Observaciones |
|---|---|---|---|---|---|
| P01 | Pendiente | Sin ejecutar | Pendiente | - | - |
| P02 | Pendiente | Sin ejecutar | Pendiente | - | - |
| P03 | Pendiente | Sin ejecutar | Pendiente | - | - |
| P04 | Pendiente | Sin ejecutar | Pendiente | - | - |
| P05 | Pendiente | Sin ejecutar | Pendiente | - | - |

## 5. Gestión de errores

Cuando una prueba no alcance el resultado esperado, se registrará una incidencia en GitHub Issues, indicando los pasos necesarios para reproducir el problema.

Una vez aplicada la corrección, se repetirá la prueba y se actualizará su resultado en este documento.

Las capturas y evidencias podrán guardarse en la carpeta `docs/evidencias/`, utilizando nombres relacionados con cada prueba, como `P02-validacion-formulario.png`.

No se utilizarán datos personales de clientes reales en las pruebas ni en las evidencias publicadas.

## 6. Estado actual

Los cinco casos de prueba están definidos, pero todavía no se han ejecutado. Sus resultados se incorporarán progresivamente durante la implementación de DulceReserva.
