---
type: ui
name: text
---

# Texto de interfaz

## Definición

Un texto de interfaz comunica contenido mediante una estructura semántica y una presentación que debe conservar su significado cuando cambia el contexto visual.

## Criterios

### Semántica

- ¿Qué función cumple el texto dentro del documento?
- ¿Es un encabezado, párrafo, énfasis, texto importante, cita, código, contenido preformateado, dirección o valor temporal?
- ¿La jerarquía de encabezados representa la estructura real del contenido?
- ¿El significado depende de una apariencia visual que debería expresarse mediante semántica?

### Idioma y dirección

- ¿Cuál es el idioma del texto?
- ¿Existen fragmentos en un idioma diferente?
- ¿Cómo se identifica cada cambio de idioma significativo?
- ¿La dirección del texto requiere tratamiento bidireccional específico?

### Espacios y saltos

- ¿Los espacios consecutivos deben preservarse o colapsarse?
- ¿Los saltos de línea deben preservarse?
- ¿El contenido preformateado debe envolver líneas o permitir desplazamiento horizontal?
- ¿Existen puntos donde puede insertarse un salto de palabra sin alterar el contenido?

### Presentación del contenido

- ¿El texto puede truncarse?
- ¿Cuál es el límite de líneas o caracteres visibles cuando se trunca?
- ¿Cómo puede accederse al contenido completo cuando existe truncamiento?
- ¿Algún significado depende exclusivamente del color, tamaño, posición o estilo tipográfico?
- Si depende de una diferencia visual, ¿qué indicador adicional comunica el mismo significado?

### Enlaces

- ¿Alguna parte del texto funciona como enlace?
- ¿Cuál es el destino de cada enlace?
- ¿El propósito del enlace puede determinarse mediante su texto y contexto accesible?
- ¿El enlace abre un nuevo contexto o ventana?
- Si abre un nuevo contexto, ¿se comunica ese comportamiento?

### Contenido dinámico

- ¿El texto puede cambiar como resultado de una acción o evento?
- Si comunica un estado o error, ¿cómo se anuncia el cambio sin mover el foco innecesariamente?
- ¿Existen reglas de localización?
- ¿Existen reglas de pluralización?
- ¿Existen valores interpolados en el contenido?
- ¿Qué debe ocurrir cuando falta un valor de interpolación?

### Adaptación

- ¿El texto permanece legible cuando cambia el tamaño de fuente, espaciado o zoom?
- ¿Qué comportamiento debe tener al reducirse el espacio disponible?
