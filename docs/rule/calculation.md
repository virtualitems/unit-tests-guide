---
type: rule
name: calculation
---

# Cálculo

## Definición

Una regla de cálculo establece cómo obtener un valor a partir de otros valores mediante una fórmula, relación o procedimiento definido.

## Criterios

### Entradas

- ¿Qué valores participan en el cálculo?
- ¿Qué unidad tiene cada entrada?
- ¿Qué debe ocurrir cuando una entrada está ausente?
- ¿Qué debe ocurrir cuando una entrada es `null`?
- ¿Qué datos variables, como la fecha actual o una tasa externa, forman parte explícita de las entradas?

### Fórmula

- ¿Cuál es la fórmula o relación exacta entre las entradas y el resultado?
- ¿Qué operadores se aplican?
- ¿En qué orden se aplican los operadores?
- ¿Existen reglas de cálculo dependientes?
- ¿Qué versión de una regla dependiente debe utilizarse?

### Unidades y precisión

- ¿Qué unidad tiene el resultado?
- ¿Se realizan conversiones de unidades?
- ¿Qué precisión se conserva?
- ¿Qué escala decimal se conserva?
- ¿Qué modo de redondeo se utiliza?
- ¿En qué paso se aplica el redondeo?

### Límites y errores

- ¿Existe un mínimo para el resultado?
- ¿Existe un máximo para el resultado?
- ¿Se aplica un tope después del cálculo?
- ¿Qué debe ocurrir ante una división por cero?
- ¿Qué debe ocurrir cuando una entrada está fuera del dominio permitido?
- ¿Qué debe ocurrir cuando el resultado no puede representarse?
- ¿Qué debe ocurrir si una fuente externa necesaria no está disponible?

### Resultado

- ¿Debe conservarse algún valor intermedio como parte del resultado observable?
- ¿Las mismas entradas, contexto y versión de reglas deben producir el mismo resultado?
