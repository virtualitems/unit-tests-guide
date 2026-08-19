---
type: rule
name: validation
---

# Validación

## Definición

Una regla de validación determina si un valor, estado, conjunto de información o acción cumple las condiciones requeridas para considerarse válido.

## Criterios

### Objeto

- ¿Qué valor, estado, conjunto de información o acción se valida?
- ¿En qué momento se ejecuta la validación?
- ¿Qué contexto adicional participa en la validación?

### Condiciones

- ¿Qué condiciones debe cumplir para considerarse válido?
- Si existen varias condiciones, ¿deben cumplirse todas?
- ¿Existen conjuntos alternativos de condiciones válidas?
- ¿Qué límites o valores frontera forman parte de la validación?
- ¿Qué condición se aplica cuando un dato está ausente?
- ¿Qué condición se aplica cuando un dato es `null`?

### Resultado

- ¿El resultado es únicamente válido o inválido?
- ¿Puede existir un resultado indeterminado?
- ¿Debe identificarse cada condición incumplida?
- ¿Cada incumplimiento tiene un código estable?
- ¿Cada incumplimiento tiene un mensaje destinado al usuario o consumidor?
- ¿El orden de los errores forma parte del contrato?
- ¿Se devuelven todos los incumplimientos o se detiene la evaluación en el primero?

### Dependencias

- ¿La validación depende de otros valores o estados?
- ¿La validación depende de una fuente externa?
- ¿Qué debe ocurrir si una dependencia necesaria no está disponible?
- ¿La validación depende de una versión de reglas o fecha de vigencia?

### Determinismo

- ¿Las mismas entradas, contexto y versión de reglas deben producir el mismo resultado?
- ¿Qué datos variables deben formar parte explícita de las entradas para que el resultado sea reproducible?
