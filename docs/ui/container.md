---
type: ui
name: container
---

# Contenedor

## Definición

Un contenedor agrupa contenido o controles y puede aportar estructura semántica, distribución visual o ambas.

## Criterios

### Contenido

- ¿Qué elementos contiene?
- ¿Cuál es el orden lógico del contenido?
- ¿El orden visual puede diferir del orden del documento?
- Si difiere, ¿el orden de lectura y foco debe conservar el orden lógico?

### Semántica

- ¿Qué función semántica cumple el contenedor?
- ¿Representa contenido principal, navegación, sección, artículo, contenido complementario, encabezado o pie?
- Si existen varios contenedores con la misma función semántica, ¿qué nombre accesible distingue cada uno?
- Si representa una región o sección, ¿qué encabezado o nombre identifica su propósito?
- ¿Establece un idioma distinto del documento?
- ¿Establece una dirección de texto distinta del documento?

### Visibilidad e interacción

- ¿Puede ocultarse o colapsarse?
- ¿Qué ocurre con el foco cuando se oculta el contenido que lo contiene?
- ¿Qué control abre o cierra el contenedor cuando es colapsable?
- ¿Cómo se comunica su estado expandido o contraído?
- Si el contenedor completo es interactivo, ¿qué acción ejecuta y cómo se evitan controles interactivos anidados con semántica incompatible?

### Distribución

- ¿Qué debe ocurrir cuando el contenido desborda horizontalmente?
- ¿Qué debe ocurrir cuando el contenido desborda verticalmente?
- ¿El contenido debe reorganizarse al reducir el ancho disponible?
- ¿Qué información o funcionalidad debe permanecer disponible al aumentar zoom o tamaño de texto?

### Navegación directa

- ¿El contenedor puede ser destino de navegación interna?
- Si puede ser destino, ¿debe recibir foco programático o quedar anunciado al llegar?
