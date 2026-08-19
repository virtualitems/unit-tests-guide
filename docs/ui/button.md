---
type: ui
name: button
---

# Botón

## Definición

Un botón es un control interactivo que ejecuta una acción. La navegación hacia otro recurso se representa mediante un enlace cuando esa es la semántica del elemento.

## Criterios

### Acción

- ¿Qué acción ejecuta el control?
- ¿El elemento ejecuta una acción o navega a otro recurso?
- Si pertenece a un formulario, ¿su función es enviar, restablecer o ejecutar una acción independiente?
- ¿La acción puede activarse más de una vez mientras una ejecución anterior está en curso?
- ¿Una acción destructiva requiere confirmación o posibilidad de deshacer?

### Contenido

- ¿Qué texto visible debe mostrar?
- ¿Debe incluir un icono?
- Si solo muestra un icono, ¿qué nombre accesible identifica la acción?
- ¿Existe texto auxiliar o tooltip?
- ¿El tooltip puede descubrirse mediante teclado y puntero?

### Estados

- ¿En qué condiciones está habilitado?
- ¿En qué condiciones está deshabilitado?
- ¿Puede tener estado de carga?
- ¿La carga bloquea activaciones duplicadas?
- ¿Puede representar éxito o error después de ejecutarse?
- ¿Es un control de alternancia con estados activado y desactivado?
- ¿Controla contenido expandible con estados expandido y contraído?
- ¿Cómo se comunica cada estado de forma programática y sin depender solo del color?

### Teclado y foco

- ¿Puede activarse mediante las teclas correspondientes a su semántica?
- ¿El foco de teclado es visible?
- ¿Dónde debe quedar el foco después de ejecutar la acción?
- ¿El área de activación cumple el tamaño mínimo definido por la política de accesibilidad del producto?

### Navegación

- Si el elemento navega, ¿cuál es el destino?
- ¿La navegación abre un nuevo contexto o ventana?
- Si abre un nuevo contexto, ¿ese comportamiento se comunica al usuario?

### Adaptación

- ¿Qué debe cambiar cuando el espacio disponible no permite mostrar el contenido completo?
- ¿Qué debe conservarse al aumentar zoom o tamaño de texto?
