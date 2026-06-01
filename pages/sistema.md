# Conoce la aplicación

Plataforma modular para la administración de condominios. Cada módulo está diseñado para cubrir una necesidad específica de la mesa directiva y los residentes.

---

## Dashboard

Panel de control central con indicadores clave, gráficos de ingresos/egresos y acceso rápido a los módulos principales.

![Dashboard](../assets/screenshots/aplicacion_1.png)

---

## Catálogo de casas

Registro completo de cada unidad del condominio: número de casa, propietario, correo electrónico y teléfono. Base para la generación de estados de cuenta y comunicación automatizada.

![Catálogo de casas](../assets/screenshots/aplicacion_3.png)

![Detalle de catálogo](../assets/screenshots/aplicacion_10.png)

---

## Catálogo de ingresos y egresos

Clasificación personalizable de conceptos:

- **Ingresos:** Multas, tarjetas de acceso, llaves, cuotas extraordinarias
- **Egresos:** Recolección de basura, electricidad, lectura de agua, jardinería, mantenimiento general

![Ingresos](../assets/screenshots/aplicacion_4.png) | ![Egresos](../assets/screenshots/aplicacion_5.png)
:---:|:---:

---

## Módulo de ingresos y egresos

Registro diario de transacciones con selección de tipo, descripción y comprobante de pago (imagen).

![Registro de ingresos](../assets/screenshots/aplicacion_6.png)

![Registro de egresos](../assets/screenshots/aplicacion_7.png)

---

## Generación de estados de cuenta

El sistema genera automáticamente estados de cuenta detallados para cada propietario y los envía por correo electrónico sin intervención manual.

![Estado de cuenta](../assets/screenshots/aplicacion_2.png)

**Flujo de operación:**

1. La mesa directiva registra la información de casas y propietarios
2. Se registran las cuotas de mantenimiento periódicas
3. Se registran los gastos del condominio
4. El sistema genera los estados de cuenta automáticamente
5. Los estados de cuenta se envían por correo a cada propietario

---

## Módulo de videovigilancia

Acceso a cámaras IP en tiempo real vía protocolo RTSP directamente desde la aplicación web.

![Videovigilancia](../assets/screenshots/aplicacion_8.png)

**Requerimientos:**
- Raspberry Pi 3 o 4 como NVR (grabador de red)
- Almacenamiento de hasta 5 días de eventos
- Compatible con cámaras Dahua, Hilook, IPCOM

---

[← Volver al inicio](../README.md)
