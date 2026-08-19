---
type: value
name: number
---

# Número

## Definición

Un número es un valor que expresa una cantidad, magnitud, posición o relación matemática.

## Criterios

### Presencia

- ¿Puede estar ausente?
- ¿Puede ser `null`?
- ¿Ausencia, `null` y cero representan estados distintos?
- ¿Existe un valor predeterminado?
- ¿Cómo se obtiene el valor predeterminado cuando no es constante?

### Tipo numérico

- ¿El valor representa un entero?
- ¿El valor representa un decimal exacto?
- ¿El valor representa un número de punto flotante?
- ¿Se permiten valores negativos?
- ¿Se permite cero?
- ¿Se permiten valores positivos?

### Rango

- ¿Existe un valor mínimo?
- ¿El valor mínimo es inclusivo o exclusivo?
- ¿Existe un valor máximo?
- ¿El valor máximo es inclusivo o exclusivo?
- ¿Existen valores específicos que deban rechazarse aunque estén dentro del rango permitido?
- ¿El valor debe ser múltiplo de una cantidad o respetar un paso determinado?

### Precisión

- ¿Cuál es la precisión total máxima?
- ¿Cuál es la escala decimal máxima o exacta?
- ¿Deben conservarse los ceros finales porque representan precisión significativa?
- ¿Qué modo de redondeo debe utilizarse?
- ¿En qué momento se aplica el redondeo?
- ¿La comparación exige igualdad exacta o admite tolerancia?
- ¿Qué tolerancia absoluta se admite, si corresponde?
- ¿Qué tolerancia relativa se admite, si corresponde?

### Unidad

- ¿Qué unidad representa el valor?
- ¿Se permiten valores expresados en otras unidades?
- ¿Qué regla de conversión se utiliza entre unidades?
- ¿Qué precisión y redondeo se aplican después de convertir una unidad?

### Representación

- ¿Se permiten ceros a la izquierda?
- ¿Se permite notación científica como entrada?
- ¿Se permite notación científica como salida?
- ¿El separador decimal depende de la representación localizada o forma parte del valor intercambiado?
- ¿Los separadores de miles se aceptan en la entrada?
- ¿Existe una representación canónica para serializar el número?

### Límites de representación

- ¿Qué debe ocurrir si el valor excede la capacidad de la representación numérica utilizada?
- ¿Qué debe ocurrir ante underflow?
- ¿Se permiten `NaN` o infinito cuando la plataforma puede representarlos?
- ¿El cero negativo se considera equivalente a cero cuando la plataforma puede representarlo?
