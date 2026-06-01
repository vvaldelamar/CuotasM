# Iniciar en la aplicación

Guía de onboarding para nuevas comunidades. El proceso consta de cuatro fases.

---

## 1. Migración de datos

El primer paso es migrar el historial de pagos desde el administrador anterior.

- El cliente entrega los registros completos de pagos (Excel, base de datos, etc.)
- El equipo de desarrollo ejecuta procesos ETL automatizados para importar los datos
- Se programa una reunión para revisar la migración junto con la mesa directiva
- Se generan estados de cuenta aleatorios para verificar la exactitud de los datos

---

## 2. Registro de casas

La mesa directiva o los administradores entregan un catálogo completo de las unidades del condominio, incluyendo:

- Número de casa
- Nombre del propietario
- Correo electrónico
- Teléfono

Consulta el [módulo de catálogo de casas](sistema.md#catálogo-de-casas) para más detalle.

---

## 3. Monto de cuotas de mantenimiento

La mesa directiva define:

- **Monto** de la cuota periódica
- **Periodicidad** (mensual, bimestral, etc.)

Estos valores se configuran como constantes en el sistema y se reflejan automáticamente en los estados de cuenta.

---

## 4. Periodicidad de estados de cuenta

Se acuerda:

- **Contenido** de los estados de cuenta (gráficos, detalle de movimientos, saldos)
- **Frecuencia de envío** (mensual, quincenal, etc.)
- **Dialogo de correo electrónico** (formato, destinatarios, asunto)

El sistema genera y envía los estados de cuenta automáticamente según la programación definida.

![Programación de envíos](../assets/images/scheduler_1.png)

---

Con estas funcionalidades, la plataforma ofrece a la mesa directiva control total sobre la administración financiera del condominio, reduciendo la carga operativa y mejorando la transparencia con los propietarios.

[← Volver al inicio](../README.md)
