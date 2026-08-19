---
type: rule
name: decision
---

# Decisión

## Definición

Una regla de decisión selecciona uno o más resultados entre alternativas definidas según los datos y condiciones presentes.

## Criterios

### Entradas

- ¿Qué datos participan en la decisión?
- ¿Qué contexto participa en la decisión?
- ¿Qué debe ocurrir cuando falta un dato necesario?
- ¿Puede existir un resultado indeterminado?

### Alternativas

- ¿Cuáles son los resultados posibles?
- ¿Existe un resultado predeterminado cuando ninguna condición coincide?
- ¿Puede producirse más de un resultado?

### Condiciones

- ¿Qué condiciones conducen a cada resultado?
- ¿Puede coincidir más de una condición al mismo tiempo?
- ¿Qué política se aplica cuando coinciden varias condiciones?
- ¿Se exige una única coincidencia?
- ¿Se toma la primera coincidencia según un orden definido?
- ¿Existe una prioridad explícita entre coincidencias?
- ¿Se recopilan todos los resultados coincidentes?
- ¿Cómo se agregan varios resultados cuando la política permite más de uno?

### Dependencias

- ¿La decisión depende de otras decisiones?
- ¿Cómo se resuelven conflictos entre decisiones dependientes?
- ¿Qué debe ocurrir si una decisión dependiente no puede evaluarse?

### Vigencia y trazabilidad

- ¿La decisión depende de una versión de reglas?
- ¿La decisión depende de una fecha de vigencia?
- ¿Debe exponerse qué regla o condición produjo el resultado?
- ¿Las mismas entradas, contexto y versión deben producir el mismo resultado?
