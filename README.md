# Actividad 12 - Gestión de Incidentes de Software

## Descripción

Este repositorio contiene el desarrollo de la Actividad 12, enfocada en la **gestión de incidentes de software** aplicada a un sistema de registro de pacientes.

El laboratorio se desarrolló tomando como referencia un proceso de gestión basado en buenas prácticas de PMBOK, orientado a documentar, clasificar, priorizar, hacer seguimiento y cerrar incidentes reportados por los usuarios.

## Objetivo

Implementar un proceso básico para la gestión de incidentes de software, utilizando una herramienta de seguimiento que permita registrar incidentes, clasificarlos, monitorear su estado y documentar las soluciones aplicadas.

## Herramientas utilizadas

- **GitHub Issues:** registro y seguimiento de incidentes.
- **GitHub Labels:** clasificación por tipo y prioridad.
- **GitHub Projects:** tablero Kanban para visualizar el flujo de atención.
- **GitHub Repository:** almacenamiento de la documentación e informe final.

## Flujo del proceso de gestión de incidentes

El proceso definido para la atención de incidentes es el siguiente:

1. Reporte del incidente por el usuario.
2. Análisis inicial y reproducción.
3. Priorización basada en impacto.
4. Asignación al equipo de desarrollo.
5. Diagnóstico de la causa raíz.
6. Desarrollo de la solución.
7. Pruebas de la solución.
8. Cierre y verificación con el usuario.
9. Documentación de lecciones aprendidas.

## Categorización de incidentes

Los incidentes fueron clasificados mediante etiquetas en GitHub.

### Tipo de incidente

- **bug:** errores o fallas del sistema.
- **mejora:** solicitudes para optimizar funcionalidades.
- **tarea:** actividades internas del equipo.
- **seguridad:** incidentes relacionados con accesos, vulnerabilidades o protección de datos.

### Prioridad

- **prioridad alta:** requiere atención inmediata.
- **prioridad media:** afecta el funcionamiento, pero no detiene completamente el sistema.
- **prioridad baja:** incidente menor o solicitud no urgente.

## Incidentes registrados

Durante el laboratorio se registraron incidentes de ejemplo relacionados con el sistema de pacientes:

| Incidente | Tipo | Prioridad | Estado | Solución propuesta |
|---|---|---|---|---|
| Error al registrar paciente con documento duplicado | Bug | Alta | Reportado | Implementar validación para impedir registros con documentos repetidos. |
| Lentitud al consultar historial médico | Bug | Media | En análisis | Revisar consultas a la base de datos y optimizar la carga de información. |
| Mejorar validación de campos obligatorios | Mejora | Baja | Priorizado | Agregar validaciones en el formulario para evitar datos incompletos. |

## Métricas definidas

Para el seguimiento del proceso se definieron métricas básicas:

| Métrica | Descripción |
|---|---|
| Tiempo promedio de respuesta | Tiempo estimado para revisar inicialmente un incidente reportado. |
| Incidentes abiertos vs cerrados | Comparación entre los casos pendientes y solucionados. |
| Tipos de incidentes más frecuentes | Identificación de los tipos de incidentes más repetidos. |
| Incidentes por módulo o función | Identificación de los módulos con mayor número de reportes. |

## Evidencias del taller

El repositorio incluye evidencias del desarrollo de la actividad, tales como:

- Configuración de GitHub Issues.
- Creación de etiquetas o labels.
- Registro de incidentes de ejemplo.
- Configuración del tablero en GitHub Projects.
- Documentación del proceso de gestión de incidentes.
- Informe final en formato PDF.

## Informe final

El informe final de la actividad se encuentra en este repositorio en formato PDF.


