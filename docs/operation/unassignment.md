---
type: operation
name: unassignment
---

# Desasignación

## Definición

Una desasignación es una operación que elimina una relación de asignación existente entre elementos.

## Criterios

### Relación

- ¿Qué elemento deja de estar asignado?
- ¿De quién o de qué deja de estar asignado?
- ¿Qué relación concreta debe eliminarse?
- ¿Cómo se identifica la relación cuando existen varias?

### Precondiciones

- ¿Qué condiciones deben cumplirse para desasignar?
- ¿Qué reglas de autorización deben cumplirse?
- ¿Qué debe ocurrir si la relación no existe?
- ¿Qué debe ocurrir si la relación es obligatoria y no puede eliminarse sin reemplazo?

### Resultado

- ¿Qué relaciones deben dejar de existir?
- ¿Qué relaciones deben conservarse?
- ¿Debe crearse una relación sustituta?
- ¿Debe registrarse quién realizó la desasignación y cuándo?
- ¿Qué estado debe tener el elemento después de quedar sin asignación?

### Repetición y concurrencia

- ¿Repetir la misma desasignación produce el mismo resultado observable?
- ¿Qué debe ocurrir si la relación cambia antes de completar la operación?
- ¿La desasignación y sus efectos asociados son atómicos?
