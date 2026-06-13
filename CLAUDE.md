# Orienta

Catálogo digital para el orientador/a escolar: casos típicos de alumnos y
familias con dificultades, con pautas de actuación, recursos y plantillas.

## Idioma
Todo el contenido se escribe en español.

## Estructura del repo
- `/casos`: un archivo por caso típico (acoso escolar, absentismo,
  dificultades de aprendizaje, conflictos familiares...) con pautas de
  actuación paso a paso. Siguen el formato de `plantillas/plantilla-caso.md`.
- `/recursos`: enlaces, lecturas, contactos y materiales de apoyo,
  organizados por tema. Los casos pueden enlazar aquí.
- `/plantillas`: documentos reutilizables (informes, cartas a familias,
  registros de seguimiento, la plantilla de caso, etc.).
- `/herramientas`: utilidades HTML/JS autocontenidas (sin build ni
  servidor) que se abren directamente en el navegador y guardan los datos
  en localStorage del dispositivo.

## Convenciones
- Nombres de archivo en minúsculas y con guiones, ej: `acoso-escolar.md`.
- Contenido claro y práctico, pensado para consultarse rápido en el día a día.
- Nuevos casos parten de `plantillas/plantilla-caso.md`.

## Datos sensibles de alumnado
Nunca incluir nombres reales ni datos identificativos de alumnos/familias
en este repositorio (puede ser público). Los informes con datos reales se
guardan como documentos en el Drive del orientador (carpeta del caso
correspondiente), nunca en este repo. En el repo solo van plantillas
genéricas/anonimizadas y herramientas sin datos.

## Estado actual
Estructura de carpetas con casos de ejemplo y plantillas reutilizables.
Primera herramienta añadida: `herramientas/seguimiento-semanal.html`
(registro semanal con resumen visual y mensaje para familias, sin
dependencias externas). El resto del contenido sigue siendo Markdown.
