---
type: operation
name: modification
---

# Modificación

## Definición

Una modificación es una operación que cambia uno o más aspectos de un elemento existente conservando su identidad.

## Criterios

### Elemento

- ¿Qué elemento se modifica?
- ¿Cómo se identifica el elemento?
- ¿Qué debe ocurrir si el elemento no existe?

### Cambios permitidos

- ¿La operación reemplaza el estado completo o aplica cambios parciales?
- ¿Qué datos, propiedades o relaciones pueden modificarse?
- ¿Qué datos, propiedades o relaciones son inmutables?
- En una modificación parcial, ¿qué significa omitir un campo?
- ¿Qué significa enviar `null` de forma explícita?
- ¿Qué valores deben conservarse cuando no forman parte del cambio?

### Precondiciones

- ¿Qué condiciones deben cumplirse antes de modificar?
- ¿Qué reglas de validación debe cumplir el estado resultante?
- ¿Qué reglas de autorización deben cumplirse?
- ¿Qué invariantes deben mantenerse?

### Resultado

- ¿Qué valor debe tener cada propiedad modificada?
- ¿Qué relaciones deben cambiar?
- ¿Qué relaciones deben conservarse?
- ¿Qué versión o timestamp debe cambiar?
- ¿Qué debe ocurrir si la modificación no produce una diferencia efectiva?

### Atomicidad y concurrencia

- ¿La modificación es atómica?
- ¿Puede existir éxito parcial?
- ¿Qué debe revertirse si falla una parte?
- ¿Cómo se detecta que el elemento cambió desde que fue leído?
- ¿Qué debe ocurrir cuando falla una precondición de versión?
- ¿Cómo se resuelven dos modificaciones concurrentes?

### Repetición y efectos

- ¿Repetir exactamente la misma modificación produce el mismo estado final?
- ¿Qué efectos secundarios forman parte del contrato?
- ¿Qué debe ocurrir si un efecto secundario falla?
