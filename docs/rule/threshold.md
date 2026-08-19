---
type: rule
name: threshold
---

# Umbral

## Definición

Un umbral es una regla que utiliza uno o más valores de referencia para establecer fronteras, rangos o puntos a partir de los cuales cambia una condición o resultado.

## Criterios

### Valor evaluado

- ¿Qué valor se compara con el umbral?
- ¿Qué unidad utiliza el valor?
- ¿Qué precisión utiliza la comparación?

### Umbrales

- ¿Cuál es el valor de cada umbral?
- ¿Cada límite es inclusivo o exclusivo?
- ¿Los umbrales forman rangos continuos?
- ¿Existen espacios entre rangos?
- ¿Existen solapamientos entre rangos?
- ¿Qué resultado corresponde exactamente al valor frontera?

### Resultado

- ¿Qué condición o resultado produce cada rango?
- ¿Existe un resultado para valores inferiores a todos los umbrales?
- ¿Existe un resultado para valores superiores a todos los umbrales?
- ¿Existe un resultado predeterminado cuando ningún rango coincide?

### Variación

- ¿Los umbrales son constantes?
- ¿Los umbrales dependen de otra regla, configuración o versión?
- ¿Los umbrales cambian con el tiempo?
- ¿Qué fecha de vigencia corresponde a cada conjunto de umbrales?
- ¿Se necesita histéresis para evitar cambios repetidos alrededor de una frontera?
- Si existe histéresis, ¿qué umbral se utiliza para entrar y cuál para salir de un estado?

### Datos inválidos

- ¿Qué debe ocurrir cuando el valor evaluado está ausente?
- ¿Qué debe ocurrir cuando el valor no puede compararse con el umbral?
