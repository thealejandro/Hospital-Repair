# Hospital Repair

Segunda iteración (diciembre de 2018) del sistema de turnos para las clínicas del Hospital Nuestra Señora del Carmen (Cobán, Alta Verapaz), hecha en VB.NET con WPF.

## Contexto

- Año: 2018.
- Proyecto de estudiante. Continúa el prototipo [Tickets](https://github.com/thealejandro/Tickets) y fue reemplazado en 2019 por [HospitalNSC](https://github.com/thealejandro/HospitalNSC), la versión más completa.
- Es un esqueleto de interfaz: las ventanas y la navegación existen, pero la mayoría de la lógica aún no estaba implementada.
- Proyecto histórico, sin mantenimiento. Lo conservo como registro de mi trayectoria; la versión actual de esta idea son xaCare y xaSeguros, en https://xacode.dev.

## Funcionalidades observadas en el código

- Inicio de sesión con roles Administrador, Doctor y Secretaria contra MySQL (base `dbturnos`).
- Ventana Doctores: carga el panel correspondiente al doctor autenticado y marca su estado activo/inactivo en la base.
- Ventana Secretarias: menú con generador de ticket, panel de espera y configuración (sin lógica todavía) y apertura de la ventana "Sala de Espera".
- Ventana Administrador: solo menú (cerrar sesión / salir).
- Diez paneles de doctor (`PanelsDR/`) vacíos.
- Diálogos de confirmación con Material Design.

## Tecnologías

- VB.NET, WPF, .NET Framework 4.6.1.
- MaterialDesignThemes 2.5, MySql.Data 8.0.13.

## Cómo abrirlo

Abrir `Hospital Repair.sln` en Visual Studio 2017 o superior y restaurar los paquetes NuGet. Requiere un MySQL local con la base `dbturnos` (el esquema no está incluido).

## Estado

Proyecto histórico, sin mantenimiento. No incluye archivo de licencia.
