---
type: ui
name: menu
---

# Menú

## Definición

Un menú presenta un conjunto de opciones de navegación o acciones. Su patrón de interacción depende de si representa navegación de sitio o un widget de aplicación.

## Criterios

### Tipo

- ¿El componente representa navegación de sitio?
- ¿El componente representa un menú de acciones de aplicación?
- ¿Qué nombre accesible identifica la navegación o menú?

### Activación

- ¿El menú está siempre visible o se abre mediante un control?
- ¿Qué nombre tiene el control que lo abre?
- ¿Cómo comunica el control si el menú está expandido o contraído?
- ¿Cómo se relaciona programáticamente el control con el contenido que abre?
- ¿El menú puede abrirse mediante hover?
- Si se abre mediante hover, ¿existe también un mecanismo mediante teclado y puntero explícito?
- ¿Qué comportamiento tiene en dispositivos táctiles?

### Foco y teclado

- ¿Qué elemento recibe foco al abrir el menú?
- ¿Qué elemento recibe foco al cerrar?
- ¿Cerrar con Escape devuelve el foco al control activador?
- ¿Qué teclas permiten recorrer las opciones según el patrón utilizado?
- ¿Se admiten Home y End cuando el patrón lo requiere?
- ¿Se admite búsqueda por escritura cuando el patrón lo requiere?
- ¿Cómo se navegan submenús mediante teclado?

### Cierre y selección

- ¿El menú se cierra después de seleccionar una opción?
- ¿Se cierra al presionar Escape?
- ¿Se cierra al interactuar fuera de su contexto?
- ¿Qué ocurre al abrir un menú mientras otro está abierto?
- ¿Qué diferencia existe entre una opción deshabilitada, seleccionada y correspondiente a la ubicación actual?

### Posicionamiento

- ¿Dónde se muestra el menú respecto de su activador?
- ¿Cómo se reposiciona cuando no hay espacio suficiente en el viewport?
- ¿Qué ocurre cuando el menú es más alto que el viewport?
- ¿Puede desplazarse internamente?
- ¿Qué ocurre con el estado abierto y el foco cuando cambia la distribución de la interfaz?
