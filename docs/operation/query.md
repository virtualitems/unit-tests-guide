---
type: operation
name: query
---

# Consulta

## Definición

Una consulta es una operación que obtiene información sin modificar el estado del objeto consultado.

## Criterios

### Fuente

- ¿Qué conjunto de información se consulta?
- ¿Qué reglas de autorización limitan la información visible?
- ¿La consulta debe observar una instantánea consistente de los datos?

### Filtros

- ¿Qué filtros se admiten?
- ¿Qué operador admite cada filtro?
- ¿Cómo se combinan varios filtros?
- ¿Se permiten grupos lógicos `AND` y `OR`?
- ¿Qué significa que un filtro esté ausente?
- ¿Qué significa que un filtro esté vacío?
- ¿Qué significa que un filtro sea `null`?
- ¿Las comparaciones de texto distinguen mayúsculas y minúsculas?
- ¿Las comparaciones de texto distinguen acentos?
- ¿Qué locale o normalización utiliza una comparación textual?
- ¿Qué zona horaria utiliza una comparación temporal?

### Proyección

- ¿Qué datos contiene cada resultado?
- ¿Puede solicitarse un subconjunto de campos?
- ¿Qué campos nunca deben exponerse aunque se soliciten?

### Orden

- ¿Cuál es el orden predeterminado?
- ¿Qué campos pueden utilizarse para ordenar?
- ¿Qué direcciones de orden se admiten?
- ¿Se permiten varios criterios de orden?
- ¿Cómo se ordenan valores `null`?
- ¿Qué criterio de desempate garantiza un orden determinista?

### Paginación

- ¿La consulta utiliza paginación?
- ¿La paginación usa página y offset, cursor u otro mecanismo?
- ¿Cuál es el tamaño predeterminado de página?
- ¿Cuál es el tamaño máximo de página?
- ¿Se devuelve el total de resultados?
- ¿El total es exacto o aproximado?
- ¿Qué debe ocurrir con una página o cursor inválido?
- ¿Qué garantía existe frente a inserciones, eliminaciones o cambios entre páginas?

### Resultado

- ¿Qué representa una consulta sin coincidencias?
- ¿Existe un límite máximo total de resultados?
- ¿Puede la consulta reflejar cambios que ocurren durante su ejecución?
