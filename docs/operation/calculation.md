---
type: operation
name: calculation
---

# Cálculo

## Definición

Una operación de cálculo produce uno o más valores mediante la aplicación de reglas de cálculo a entradas definidas.

## Criterios

### Entradas

- ¿Qué valores utiliza la operación?
- ¿De qué fuente proviene cada valor?
- ¿Qué entradas son obligatorias?
- ¿Qué debe ocurrir cuando una entrada está ausente o no puede obtenerse?

### Reglas

- ¿Qué reglas de cálculo se aplican?
- ¿En qué orden se aplican cuando existe dependencia entre ellas?
- ¿Qué versión de cada regla se utiliza?
- ¿Qué contexto temporal o externo debe fijarse como entrada para reproducir el cálculo?

### Resultado

- ¿Qué valores debe producir la operación?
- ¿Qué unidad, precisión y representación debe tener cada resultado?
- ¿Qué resultados intermedios deben quedar disponibles?
- ¿Qué debe ocurrir si una regla no puede producir un resultado válido?

### Ejecución

- ¿La operación modifica algún estado además de producir el resultado?
- ¿Las mismas entradas, contexto y versión de reglas producen el mismo resultado?
- ¿Qué efectos secundarios forman parte del contrato, si existen?
