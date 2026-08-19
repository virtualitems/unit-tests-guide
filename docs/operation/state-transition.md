---
type: operation
name: state-transition
---

# Transición de estado

## Definición

Una transición de estado es una operación que cambia el estado de un elemento desde un estado de origen hacia un estado de destino.

## Criterios

### Estados

- ¿Cuál es el conjunto completo de estados posibles?
- ¿Cuál es el estado actual requerido para iniciar la transición?
- ¿Cuál es el estado de destino?
- ¿Qué transiciones están permitidas desde cada estado?
- ¿Qué transiciones están prohibidas?

### Precondiciones

- ¿Qué condiciones deben cumplirse para cada transición?
- ¿Qué datos deben estar presentes?
- ¿Qué reglas de autorización deben cumplirse?
- ¿Qué debe ocurrir al solicitar una transición no permitida?
- ¿Qué debe ocurrir al solicitar una transición hacia el mismo estado actual?

### Cambios e invariantes

- ¿Qué datos deben cambiar junto con el estado?
- ¿Qué relaciones deben cambiar?
- ¿Qué datos deben permanecer invariantes?
- ¿Qué relaciones deben permanecer invariantes?
- ¿La transición y sus cambios asociados son atómicos?

### Historial y efectos

- ¿Debe registrarse el actor que ejecutó la transición?
- ¿Debe registrarse la razón de la transición?
- ¿Debe registrarse el momento de la transición?
- ¿Debe conservarse el historial de estados?
- ¿Qué efectos secundarios se activan con cada transición?
- ¿Qué debe ocurrir si un efecto secundario falla después del cambio de estado?

### Automatización y concurrencia

- ¿Existen transiciones automáticas por tiempo o evento?
- ¿Cómo se resuelven dos transiciones concurrentes sobre el mismo elemento?
- ¿Puede revertirse una transición?
- ¿La reversión es una transición de dominio explícita o una compensación técnica?
