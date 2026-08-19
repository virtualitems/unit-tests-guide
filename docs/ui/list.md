---
type: ui
name: list
---

# Lista

## Definición

Una lista presenta elementos relacionados con una semántica de orden, agrupación o descripción definida.

## Criterios

### Semántica

- ¿La lista es no ordenada?
- ¿La lista es ordenada?
- ¿La lista representa pares de término y descripción?
- ¿El orden de los elementos tiene significado de dominio?
- Para una lista ordenada, ¿qué número inicial o dirección de numeración debe utilizarse?

### Elementos

- ¿Qué fuente proporciona los elementos?
- ¿Qué identifica de forma estable a cada elemento?
- ¿Qué contenido muestra cada elemento?
- ¿Se permiten listas anidadas?
- ¿Qué jerarquía deben representar los niveles anidados?
- ¿Qué debe mostrarse cuando la lista está vacía?

### Interacción

- ¿Los elementos son únicamente contenido?
- ¿Los elementos navegan a otro recurso?
- ¿Los elementos ejecutan una acción?
- ¿Los elementos pueden seleccionarse?
- ¿La selección es única o múltiple?
- ¿Cómo se comunica programáticamente el estado seleccionado?
- Si la lista actúa como un widget compuesto, ¿qué patrón de teclado corresponde a su semántica?

### Orden y carga

- ¿Los elementos pueden reordenarse?
- Si se reordenan mediante arrastre, ¿existe una operación equivalente mediante teclado?
- ¿La lista se pagina o carga elementos progresivamente?
- ¿Cómo se conserva el foco y la posición de desplazamiento al añadir elementos?
- ¿Cómo se comunica que se añadieron nuevos elementos?
- ¿El estado de paginación o carga adicional forma parte de la URL o historial navegable?

### Virtualización

- ¿La lista utiliza virtualización?
- Si se virtualiza, ¿cómo se preserva la identidad de los elementos?
- ¿Cómo se preservan posición, conteo y foco de forma observable?
