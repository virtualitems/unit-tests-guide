---
type: value
name: boolean
---

# Booleano

## Definición

Un booleano es un valor que expresa una condición mediante dos estados mutuamente excluyentes.

## Criterios

### Presencia

- ¿Puede estar ausente?
- ¿Puede ser `null`?
- ¿Ausencia, `null` y `false` representan estados distintos?
- ¿Existe un valor predeterminado?
- ¿Cuál es el valor predeterminado?

### Significado

- ¿Qué condición de dominio representa `true`?
- ¿Qué condición de dominio representa `false`?
- ¿El valor representa un hecho, una preferencia, un estado o una decisión?

### Representación

- ¿Qué representaciones externas se aceptan como `true`?
- ¿Qué representaciones externas se aceptan como `false`?
- ¿Se permite convertir valores de otros tipos a booleano?
- ¿Qué debe ocurrir ante una representación ambigua o no reconocida?
- ¿Cuál es la representación canónica al serializar el valor?

### Transiciones

- ¿Cambiar de `false` a `true` tiene condiciones o efectos propios?
- ¿Cambiar de `true` a `false` tiene condiciones o efectos propios?
