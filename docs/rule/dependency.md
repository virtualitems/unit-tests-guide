---
type: rule
name: dependency
---

# Dependencia

## Definición

Una regla de dependencia establece que una condición, estado, resultado o posibilidad depende de la existencia, estado, valor o comportamiento de otro elemento.

## Criterios

### Relación

- ¿Qué elemento depende de otro?
- ¿De qué elemento depende?
- ¿La dependencia es obligatoria u opcional?
- ¿Qué cardinalidad tiene la dependencia?
- ¿La dependencia exige una versión mínima, exacta o compatible?

### Estado requerido

- ¿La dependencia debe existir?
- ¿La dependencia debe estar disponible?
- ¿La dependencia debe estar activa?
- ¿La dependencia debe ser válida?
- ¿La dependencia debe encontrarse en un estado concreto?

### Evaluación

- ¿Cuándo se evalúa la dependencia?
- ¿Debe resolverse antes de iniciar una operación?
- ¿Puede resolverse durante la operación?
- Si existen varias dependencias, ¿se requieren todas?
- ¿Puede bastar una de varias dependencias?
- ¿Qué combinación de dependencias es válida?
- ¿Las dependencias transitivas forman parte del contrato?

### Fallos y ciclos

- ¿Se permiten ciclos de dependencia?
- ¿Qué debe ocurrir cuando se detecta un ciclo no permitido?
- ¿Qué debe ocurrir cuando una dependencia falta?
- ¿Qué debe ocurrir cuando una dependencia es inválida?
- ¿Qué debe ocurrir cuando una dependencia no está disponible?
- ¿El fallo se propaga al elemento dependiente?
- ¿Existe un comportamiento alternativo cuando falla una dependencia?
- ¿Se permite un comportamiento degradado?

### Cambio

- ¿Qué debe ocurrir con el elemento dependiente cuando cambia la dependencia?
- ¿Qué debe ocurrir cuando desaparece la dependencia?
- ¿Existe un orden o prioridad entre dependencias?
