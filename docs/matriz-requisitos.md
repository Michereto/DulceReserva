# Matriz de requisitos - DulceReserva

Este documento recoge los requisitos principales de DulceReserva y los criterios que se utilizarán para comprobar su cumplimiento.

La matriz relaciona cada requisito con una comprobación prevista y con las evidencias que deberán conservarse durante el desarrollo.

Actualmente todos los requisitos están pendientes de verificación.

## 1. Matriz de requisitos y criterios de aceptación

| ID | Requisito | Criterio de aceptación | Comprobación prevista | Evidencia | Estado |
|---|---|---|---|---|---|
| R01 | Inicio de sesión | Los usuarios acceden con credenciales válidas y se identifica correctamente su rol | Probar accesos correctos e incorrectos | Captura del acceso y registro de prueba | Pendiente |
| R02 | Permisos de usuarios | Tienda puede gestionar encargos; obrador puede consultar y marcar como preparado, pero no modificar los datos del encargo | Intentar modificar un encargo desde el rol de obrador (P04) | Prueba de permisos y captura del resultado | Pendiente |
| R03 | Registro de encargos | Los datos obligatorios del cliente y del pedido se guardan correctamente | Crear un encargo y consultar sus datos (P01) | Registro de prueba y datos guardados | Pendiente |
| R04 | Validación de formularios | No se permiten encargos sin los campos obligatorios o con datos inválidos | Enviar formularios incompletos o incorrectos (P02) | Captura de los avisos y resultado de la prueba | Pendiente |
| R05 | Disponibilidad y capacidad | Se consultan los productos activos y se avisa cuando se supera la capacidad configurada | Registrar un encargo en una franja con sobrecarga (P03) | Captura del aviso y registro de prueba | Pendiente |
| R06 | Gestión de encargos | Tienda puede buscar, modificar y cancelar encargos | Realizar cada operación y comprobar los cambios | Capturas y registros de pruebas | Pendiente |
| R07 | Estados de encargos | Se gestionan correctamente los estados pendiente, preparado, recogido y cancelado según los permisos | Cambiar estados desde los perfiles autorizados | Captura del estado actualizado | Pendiente |
| R08 | Previsión diaria | Se muestran las cantidades de producción previstas para una fecha | Registrar varios encargos y consultar los totales (P05) | Captura del listado y comparación de cantidades | Pendiente |
| R09 | Previsión por horas | Se pueden consultar encargos y cantidades por franja horaria | Filtrar los encargos por fecha y hora | Captura de los resultados filtrados | Pendiente |
| R10 | Encargos cancelados | Los encargos cancelados permanecen registrados, pero no cuentan para producción | Cancelar un encargo y consultar la previsión (P05) | Registro de prueba y captura de los totales | Pendiente |
| R11 | Consulta por tienda | El obrador puede filtrar los encargos según su tienda de origen | Consultar encargos de diferentes tiendas | Captura del filtro y sus resultados | Pendiente |
| R12 | Adaptación de interfaz | Las funciones principales pueden utilizarse en ordenador, tableta y móvil | Comprobar las pantallas en diferentes tamaños | Capturas de las pruebas de interfaz | Pendiente |

## 2. Estados de cumplimiento

Cada requisito podrá encontrarse en uno de los siguientes estados:

- **Pendiente:** todavía no se ha realizado la comprobación.
- **Cumplido:** se ha comprobado y el resultado coincide con el criterio de aceptación.
- **Necesita corrección:** la comprobación ha detectado un problema que debe solucionarse.

## 3. Procedimiento de verificación

Para comprobar el cumplimiento de un requisito se seguirán estos pasos:

1. Identificar el requisito que se va a verificar.
2. Preparar los datos necesarios para la comprobación.
3. Ejecutar la prueba o acción prevista.
4. Comparar el resultado obtenido con el criterio de aceptación.
5. Registrar el resultado y conservar las evidencias.
6. Actualizar el estado del requisito en esta matriz.
7. Si existe un problema, registrar una incidencia en GitHub Issues.
8. Repetir la comprobación después de aplicar la corrección.

## 4. Relación con el registro de pruebas

Las pruebas funcionales P01 a P05 están descritas en el archivo `docs/registro-pruebas.md`.

Los requisitos que no tengan asignada una prueba con identificador específico se comprobarán mediante las acciones indicadas en esta matriz. Si es necesario, se añadirán nuevos casos al registro de pruebas durante el desarrollo.

## 5. Registro de evidencias

Las evidencias podrán incluir:

- Capturas de pantalla de las funcionalidades.
- Resultados de los casos de prueba.
- Referencias a incidencias de GitHub Issues.
- Referencias a commits relacionados con la implementación.
- Comprobaciones de los datos guardados en la base de datos.

Cuando corresponda, las capturas se guardarán en `docs/evidencias/` y se identificarán mediante el requisito o la prueba relacionada.

Se utilizarán datos ficticios para evitar publicar información personal de clientes reales.

## 6. Seguimiento y actualización

La matriz se actualizará progresivamente conforme se implementen y comprueben las funcionalidades.

Si un requisito necesita corrección, permanecerá en ese estado hasta que se solucione el problema y se repita la comprobación.

La información recogida permitirá conocer qué funcionalidades están verificadas y cuáles siguen pendientes antes de finalizar DulceReserva.

## 7. Estado actual

Los doce requisitos están definidos y pendientes de verificación. Todavía no se han realizado las pruebas funcionales previstas.

Los resultados y las evidencias se incorporarán durante las siguientes fases del proyecto.
