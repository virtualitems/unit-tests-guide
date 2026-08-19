---
type: ui
name: table
---

# Tabla

## Definición

Una tabla presenta datos cuya relación depende de filas y columnas. Un grid interactivo añade navegación o edición por celdas y requiere un patrón de interacción distinto.

## Criterios

### Semántica y estructura

- ¿El contenido representa datos tabulares?
- ¿Existe un nombre o caption que identifique el propósito de la tabla?
- ¿Qué columnas contiene?
- ¿Qué celdas son encabezados de columna?
- ¿Existen encabezados de fila?
- ¿Existen encabezados agrupados o multinivel?
- Si existen encabezados complejos, ¿cómo se asocia cada celda de datos con sus encabezados?

### Datos

- ¿Cuál es la fuente de las filas?
- ¿Qué clave identifica de forma estable cada fila?
- ¿Qué valor muestra cada columna?
- ¿Existen columnas calculadas?
- ¿Existen totales o subtotales?
- ¿Los totales se calculan sobre toda la consulta o solo sobre la página visible?
- ¿Qué debe mostrarse cuando no existen filas?

### Orden y filtros

- ¿Cuál es el orden predeterminado?
- ¿Qué columnas pueden ordenar la tabla?
- ¿Cuál es el criterio de desempate?
- ¿Cómo se comunica programáticamente la columna y dirección de orden?
- ¿Qué filtros están disponibles?
- ¿Cómo se muestran los filtros activos?
- ¿Existe búsqueda de texto?
- ¿Qué columnas participan en la búsqueda?

### Selección e interacción

- ¿Las filas pueden seleccionarse?
- ¿La selección es única o múltiple?
- ¿Cómo se comunica programáticamente la selección?
- ¿La tabla permite editar celdas o navegar por ellas como un grid?
- Si funciona como grid, ¿qué patrón de teclado debe soportar?
- ¿Alguna celda contiene enlaces o acciones?
- ¿Qué semántica corresponde a cada interacción?

### Paginación y virtualización

- ¿La tabla utiliza paginación?
- ¿Cuál es el tamaño de página predeterminado?
- ¿Qué tamaños de página se permiten?
- ¿Se muestra el total de filas?
- ¿Los filtros y el orden se conservan al cambiar de página?
- ¿La tabla virtualiza filas?
- Si se virtualiza, ¿cómo se preservan identidad, foco, posición y conteo?

### Contenido y adaptación

- ¿Qué ocurre cuando el contenido de una celda excede el espacio disponible?
- ¿El contenido puede envolver líneas?
- ¿El contenido puede truncarse?
- Si se trunca, ¿el valor completo sigue disponible de forma accesible?
- ¿La tabla permite desplazamiento horizontal en espacios estrechos?
- ¿Cómo se preserva la relación entre encabezados y datos cuando cambia la distribución?
- ¿Qué estado se muestra durante carga?
- ¿Qué estado se muestra ante un error?
