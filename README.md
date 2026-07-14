# Sistema de Gestión de Turnos y Publicidad

Aplicación desarrollada con **Microsoft Power Apps**, **SharePoint Online** y **Power Fx** para administrar la emisión de turnos y mostrar información en tiempo real mediante una pantalla publicitaria.

---

# Descripción

El Sistema de Gestión de Turnos y Publicidad es una solución desarrollada con Microsoft Power Platform para administrar el proceso de atención al cliente mediante un sistema de turnos.

La solución está compuesta por dos aplicaciones que trabajan de forma integrada:

- **Cambio de Turno**, utilizada por los operadores para emitir y administrar turnos desde distintas ventanillas.
- **Turno Publicitario**, destinada a informar a los clientes el turno actual, los próximos turnos y mostrar publicidad dinámica de productos.

Ambas aplicaciones comparten el mismo origen de datos en **SharePoint Online**, permitiendo mantener toda la información sincronizada en tiempo real.

---

# Características principales

- Emisión de turnos.
- Administración de múltiples ventanillas.
- Registro automático de turnos.
- Consulta del turno actual.
- Visualización de los próximos turnos.
- Historial de turnos.
- Publicidad dinámica de productos.
- Sincronización en tiempo real entre ambas aplicaciones.
- Integración con SharePoint Online.
- Implementación de la lógica mediante Power Fx.

---

# Tecnologías utilizadas

- Microsoft Power Apps
- Power Fx
- SharePoint Online

---

# Capturas de pantalla

## Selección de ventanilla

![Selección de ventanilla](assets/seleccion-ventanilla.png)

---

## Cambio de Turno

![Cambio de Turno](assets/cambio-turno.png)

---

## Turno Publicitario

![Turno Publicitario](assets/publicidad2.png)

---

# Arquitectura

```text
                 Operador
                     │
                     ▼
      Power Apps - Cambio de Turno
                     │
                     ▼
             SharePoint Online
          ┌──────────┴──────────┐
          ▼                     ▼
   Lista de Turnos      Biblioteca Publicidad
          └──────────┬──────────┘
                     ▼
     Power Apps - Turno Publicitario
                     │
                     ▼
                  Clientes
```

---

# Documentación

La documentación completa del proyecto se encuentra disponible en:

📄 **documentacion.md**

---

# Conceptos aplicados

Durante el desarrollo se implementaron los principales conceptos de Microsoft Power Platform:

- Variables globales.
- Variables de contexto.
- Colecciones.
- Formularios.
- Navegación entre pantallas.
- Controles modernos.
- Temporizadores.
- Integración con SharePoint Online.
- Manipulación de datos mediante Power Fx (Patch, Filter, LookUp y Sort).

---

# Estado del proyecto

Proyecto finalizado.

La solución integra dos aplicaciones conectadas mediante SharePoint Online para gestionar la emisión de turnos y mostrar información en tiempo real a los clientes.

---

# Autor

**Andrea Natalia Tello**

- GitHub: [AnNaTe07](https://github.com/AnNaTe07)
- LinkedIn: [Andrea Natalia Tello](https://www.linkedin.com/in/andrea-natalia-tello-623874325/)
