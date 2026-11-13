# Indicadores de calidad - DulceReserva

Este documento recoge los indicadores que se utilizarán para comprobar la calidad de DulceReserva durante su desarrollo.

Las comprobaciones se realizarán progresivamente. Todos los indicadores están pendientes hasta que se ejecuten las pruebas correspondientes.

| ID | Indicador | Comprobación | Resultado aceptable | Momento | Estado |
|---|---|---|---|---|---|
| I01 | Registro de encargos | Crear un encargo y consultar sus datos | Datos guardados correctamente | Desarrollo del formulario | Pendiente |
| I02 | Validación de formularios | Introducir datos vacíos o incorrectos | Se muestra un aviso y no se guardan datos inválidos | Desarrollo de formularios | Pendiente |
| I03 | Disponibilidad y capacidad | Superar la capacidad configurada para una hora | Se muestra una advertencia antes de confirmar | Desarrollo de disponibilidad | Pendiente |
| I04 | Gestión de estados | Cambiar estados de un encargo | Estado actualizado correctamente | Desarrollo de estados | Pendiente |
| I05 | Permisos | Intentar modificar un encargo desde obrador | La modificación se impide | Desarrollo de roles | Pendiente |
| I06 | Previsión de producción | Consultar totales por fecha y hora | Cantidades correctas | Desarrollo de listados | Pendiente |
| I07 | Integridad de datos | Crear, modificar y cancelar encargos | Datos coherentes y cancelados excluidos de producción | Pruebas de base de datos | Pendiente |
| I08 | Diseño adaptable | Probar ordenador, tableta y móvil | Funciones esenciales utilizables | Pruebas de interfaz | Pendiente |
| I09 | Cumplimiento del cronograma | Comparar avance con hitos de Fase 3 | Hitos cumplidos o retrasos documentados | Revisión semanal | Pendiente |

## Registro de comprobaciones

| Fecha | Indicador | Resultado obtenido | Evidencia | Estado | Observaciones |
|---|---|---|---|---|---|
| Pendiente | - | Sin ejecutar | - | Pendiente | - |

Los resultados se actualizarán después de cada comprobación. Si se detecta un problema, se registrará en GitHub Issues y se repetirá la prueba después de corregirlo.
