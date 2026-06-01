# 📋 Iniciar en la aplicación

Guía de onboarding para nuevas comunidades. El proceso completo consta de cuatro fases.

---

## 📌 Progreso del onboarding

**Fase 1** ✅ —
**Fase 2** ⬜ —
**Fase 3** ⬜ —
**Fase 4** ⬜

---

## Fase 1 — Migración de datos

⏱️ **Duración estimada:** 3–5 días hábiles

El primer paso es migrar el historial de pagos desde el administrador anterior. Nuestro equipo se encarga de todo el proceso técnico.

### Checklist de la fase

- [ ] **Entrega de registros** — El cliente entrega los registros completos de pagos (Excel, base de datos, etc.)
- [ ] **Procesamiento ETL** — El equipo de desarrollo ejecuta procesos automatizados para importar los datos
- [ ] **Reunión de revisión** — Se programa una reunión para revisar la migración junto con la mesa directiva
- [ ] **Verificación** — Se generan estados de cuenta aleatorios para verificar la exactitud de los datos

> [!NOTE]
> La reunión de revisión es clave para asegurar que todos los saldos iniciales coincidan con los registros del administrador anterior.

---

## Fase 2 — Registro de casas

⏱️ **Duración estimada:** 1–2 días hábiles

La mesa directiva o los administradores entregan un catálogo completo de las unidades del condominio.

### Datos requeridos por cada unidad

| # | Dato | Propósito |
|---|------|-----------|
| 1 | **Número de casa** | Identificador único en el sistema |
| 2 | **Nombre del propietario** | Titular del estado de cuenta |
| 3 | **Correo electrónico** | Envío automatizado de estados de cuenta |
| 4 | **Teléfono** | Contacto para comunicados urgentes |

> Consulta el [módulo de catálogo de casas](../sistema/#-catálogo-de-casas) para más detalle sobre esta funcionalidad.

---

## Fase 3 — Monto de cuotas de mantenimiento

⏱️ **Duración estimada:** Medio día (en reunión con la mesa directiva)

La mesa directiva define los parámetros financieros base del sistema.

### Parámetros a configurar

- **💰 Monto** de la cuota periódica (ej. $850 MXN por mes)
- **📅 Periodicidad** (mensual, bimestral, trimestral, etc.)

Estos valores se configuran como constantes en el sistema y se reflejan automáticamente en todos los estados de cuenta. Cualquier cambio futuro se actualiza de forma centralizada.

> [!TIP]
> Recomendamos iniciar con periodicidad **mensual** para facilitar la adopción por parte de los propietarios.

---

## Fase 4 — Periodicidad de estados de cuenta

⏱️ **Duración estimada:** Medio día (en reunión con la mesa directiva)

Se acuerda la configuración final del módulo de comunicaciones.

### Decisiones a tomar

- **📄 Contenido** de los estados de cuenta (gráficos, detalle de movimientos, saldos, datos del condominio)
- **📆 Frecuencia de envío** (mensual, quincenal, semanal)
- **✉️ Formato del correo** (asunto, destinatarios en copia, diseño del mensaje)

El sistema genera y envía los estados de cuenta automáticamente según la programación definida, **sin intervención manual**.

<img src="../assets/images/scheduler_1.png" alt="Programación de envíos" width="80%" />

---

## ✅ Siguientes pasos

Una vez completadas las cuatro fases, la plataforma queda operativa y la mesa directiva tiene **control total** sobre la administración financiera del condominio.

| Beneficio | Impacto |
|-----------|---------|
| 🕐 **Reducción de carga operativa** | La mesa directiva dedica menos horas a tareas repetitivas |
| 📊 **Visibilidad en tiempo real** | Ingresos, egresos y saldos siempre actualizados |
| 🔍 **Transparencia** | Cada propietario puede consultar su historial |
| 📬 **Comunicación automatizada** | Los estados de cuenta llegan sin falta a cada correo |

<div align="center">
  <br>
  <a href="../costos/"><strong>💰 Ver planes y costos →</strong></a>
  <br><br>
  <a href="../../">← Volver al inicio</a>
</div>
