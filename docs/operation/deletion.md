---
type: operation
name: deletion
---

# Eliminación

## Definición

Una eliminación es una operación que hace que un elemento, dato o relación deje de estar disponible en el ámbito donde existía.

## Criterios

### Objetivo

- ¿Qué elemento, dato o relación se elimina?
- ¿Cómo se identifica?
- ¿Qué debe ocurrir si no existe?

### Tipo de eliminación

- ¿La eliminación es física?
- ¿La eliminación es lógica mediante un estado o marca?
- ¿Una eliminación lógica permite restauración?
- ¿Durante cuánto tiempo puede restaurarse?

### Precondiciones

- ¿Qué condiciones deben cumplirse antes de eliminar?
- ¿Qué reglas de autorización deben cumplirse?
- ¿Qué relaciones impiden la eliminación?
- ¿Qué obligaciones de retención impiden una eliminación física?

### Relaciones y datos asociados

- ¿Qué información asociada también debe eliminarse?
- ¿Qué relaciones deben eliminarse?
- ¿Qué información debe conservarse?
- ¿Qué relaciones deben conservarse?
- ¿Qué debe ocurrir con elementos dependientes?
- ¿Qué debe ocurrir con referencias externas al elemento eliminado?

### Resultado

- ¿Cómo puede verificarse que el elemento dejó de estar disponible?
- ¿Qué estado debe quedar registrado después de una eliminación lógica?
- ¿Debe conservarse evidencia de quién eliminó el elemento, cuándo y por qué?

### Repetición y concurrencia

- ¿Repetir la eliminación de un elemento ya eliminado produce el mismo resultado observable?
- ¿Cómo se detecta una modificación concurrente antes de eliminar?
- ¿Qué debe ocurrir cuando el elemento cambia antes de completar la eliminación?
- ¿La eliminación y sus efectos asociados son atómicos?
