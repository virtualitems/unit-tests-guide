---
type: rule
name: derivation
---

# Derivación

## Definición

Una regla de derivación determina un dato, estado o propiedad a partir de otros datos, estados o propiedades existentes.

## Criterios

### Fuentes

- ¿Qué datos, estados o propiedades participan en la derivación?
- ¿Qué fuente proporciona cada dato?
- ¿Qué debe ocurrir cuando falta una fuente necesaria?
- ¿Qué debe ocurrir cuando las fuentes son incompatibles o contradictorias?

### Regla

- ¿Cuál es la relación exacta entre las fuentes y el valor derivado?
- ¿El valor derivado puede proporcionarse explícitamente?
- Si existe un valor explícito y uno derivado, ¿cuál tiene precedencia?
- ¿La derivación depende de otras derivaciones?
- ¿Cómo se evita o resuelve una dependencia cíclica?

### Actualización

- ¿Cuándo debe recalcularse el valor derivado?
- ¿El valor derivado se almacena o se calcula bajo demanda?
- Si se almacena, ¿qué cambio lo vuelve obsoleto?
- ¿Qué evento obliga a actualizarlo?

### Representación y resultado

- ¿Qué normalización se aplica al resultado?
- ¿Qué precisión o redondeo se aplica al resultado?
- ¿Puede existir un resultado parcial?
- ¿El resultado debe cumplir restricciones adicionales?
- ¿Las mismas fuentes, contexto y versión deben producir el mismo resultado?
