---
type: value
name: collection
---

# Colección

## Definición

Una colección es una agrupación de valores tratados como una unidad. Puede representar una lista ordenada, un conjunto, un multiconjunto o una tupla posicional.

## Criterios

### Presencia

- ¿Puede estar ausente?
- ¿Puede ser `null`?
- ¿Ausencia, `null` y colección vacía representan estados distintos?
- ¿Existe una colección predeterminada?
- ¿Debe aceptar una colección vacía?

### Tipo de colección

- ¿Representa una lista ordenada?
- ¿Representa un conjunto sin duplicados?
- ¿Representa un multiconjunto que admite duplicados?
- ¿Representa una tupla con significado por posición?

### Cantidad

- ¿Existe una cantidad mínima de elementos?
- ¿El mínimo es inclusivo?
- ¿Existe una cantidad máxima de elementos?
- ¿El máximo es inclusivo?
- ¿Qué debe ocurrir cuando la entrada supera el máximo permitido?

### Elementos

- ¿Qué contrato debe cumplir cada elemento?
- ¿Todos los elementos comparten el mismo contrato?
- Si es una tupla, ¿qué contrato corresponde a cada posición?
- ¿Se permiten elementos `null`?
- ¿Existen elementos obligatorios por valor, categoría o condición?
- ¿Debe existir al menos un elemento que cumpla una condición determinada?
- ¿Debe existir exactamente un elemento que cumpla una condición determinada?
- ¿Existe un máximo de elementos que puedan cumplir una condición determinada?

### Identidad y duplicados

- ¿Cómo se determina que dos elementos son iguales?
- ¿La igualdad depende de una clave de identidad?
- ¿La igualdad depende de una representación normalizada?
- ¿Se permiten duplicados?
- ¿Qué debe ocurrir cuando aparece un duplicado?
- ¿Cada elemento necesita una identidad estable para actualizaciones o sincronización?

### Orden

- ¿El orden de los elementos tiene significado?
- ¿Qué comparador define el orden?
- ¿Cómo se resuelven empates?
- ¿El orden debe ser estable entre ejecuciones?
- ¿La igualdad entre colecciones considera el orden?

### Estructura

- ¿Se permiten colecciones anidadas?
- ¿Existe una profundidad máxima?
- ¿Qué debe ocurrir si un elemento de la colección es inválido?
- ¿Una entrada inválida hace fallar toda la colección o puede existir un resultado parcial?
