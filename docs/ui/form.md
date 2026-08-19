---
type: ui
name: form
---

# Formulario

## Definición

Un formulario agrupa controles para capturar, revisar y enviar datos asociados a una operación.

## Criterios

### Operación

- ¿Qué operación representa el formulario?
- ¿Cuál es la acción principal de envío?
- ¿Existen acciones adicionales como guardar borrador, enviar o cancelar?
- ¿Qué datos se envían con cada acción?
- ¿Qué método y destino de transporte forman parte del contrato cuando la interfaz debe fijarlos explícitamente?

### Campos

- ¿Qué campos contiene el formulario?
- ¿Qué nombre identifica cada campo en los datos enviados?
- ¿Qué tipo de control representa cada campo?
- ¿Qué contrato de valor debe cumplir cada campo?
- ¿Qué valor inicial tiene cada campo?
- ¿Qué fuente proporciona las opciones de un campo cuando existe un conjunto de selección?
- ¿El campo permite un único valor o varios?
- ¿El campo es editable, de solo lectura o está deshabilitado?
- ¿Qué diferencia contractual existe entre un campo de solo lectura y uno deshabilitado?
- ¿Qué propósito de autocompletado tiene el campo cuando corresponde?
- ¿Qué modo de entrada se espera en teclados virtuales cuando corresponde?

### Etiquetas e instrucciones

- ¿Qué etiqueta visible identifica cada campo?
- ¿La etiqueta está asociada programáticamente con el control?
- ¿Qué instrucciones adicionales necesita el campo?
- ¿Las instrucciones están asociadas programáticamente al control?
- ¿Qué placeholder se muestra cuando aporta información distinta de la etiqueta?
- ¿Qué ejemplo de formato debe mostrarse antes de introducir datos?
- ¿Los grupos de campos relacionados necesitan un nombre o leyenda común?

### Reglas entre campos

- ¿Qué campos son obligatorios?
- ¿Cómo se identifica programáticamente que un campo es obligatorio?
- ¿Qué campos son mutuamente excluyentes?
- ¿Qué campos dependen del valor de otros campos?
- ¿Qué campos aparecen u ocultan según otras respuestas?
- ¿Qué debe ocurrir con el valor de un campo cuando deja de ser aplicable y se oculta?
- ¿Qué límites de longitud, rango, paso o patrón forman parte del contrato de cada campo?

### Validación y errores

- ¿Qué criterios se validan antes de enviar?
- ¿Las validaciones de cliente y servidor representan los mismos criterios contractuales?
- ¿Qué datos deben preservarse después de un error de validación?
- ¿Cómo se asocia cada error con el campo correspondiente?
- ¿Cómo se comunica un error sin depender solo del color?
- ¿El formulario necesita un resumen de errores?
- Si existe un resumen, ¿dónde queda el foco después de un envío inválido?
- ¿Cómo se anuncia el éxito o error global del envío?

### Envío

- ¿Qué ocurre al presionar Enter en un control que puede provocar envío implícito?
- ¿Se impide un segundo envío mientras el primero está en curso?
- ¿Qué estado se muestra durante el envío?
- ¿Qué estado queda después de una respuesta exitosa?
- ¿Qué estado queda después de una respuesta fallida?
- ¿Qué política de autocompletado se aplica a datos sensibles?

### Colección editable

- ¿El formulario permite editar una colección de elementos?
- ¿Cuál es la cantidad mínima de elementos?
- ¿Cuál es la cantidad máxima de elementos?
- ¿Cada elemento tiene una identidad estable independiente de su posición?
- ¿Se pueden crear elementos?
- ¿Se pueden modificar elementos existentes?
- ¿Se pueden eliminar elementos existentes?
- ¿Se pueden reordenar elementos?
- ¿El orden forma parte del valor enviado?
- Si se permite arrastrar para reordenar, ¿existe una operación equivalente mediante teclado?

### Pasos

- ¿El formulario se divide en varios pasos?
- ¿Qué pasos son obligatorios?
- ¿Qué pasos son opcionales?
- ¿Puede saltarse directamente a un paso posterior?
- ¿Se validan los datos antes de avanzar?
- ¿Volver a un paso anterior conserva los datos?
- ¿Cambiar un dato anterior invalida información de pasos posteriores?
- ¿Puede guardarse el progreso para continuar después?
- ¿Cuándo expira el progreso guardado?
- ¿Cómo se informa programáticamente el paso actual y el total?
- ¿Dónde se coloca el foco al cambiar de paso?

### Disponibilidad de script y adaptación

- Si el producto exige funcionamiento sin JavaScript, ¿qué acciones deben seguir disponibles?
- ¿Qué comportamiento debe cambiar según el ancho o espacio disponible?
- ¿Qué información y controles deben permanecer disponibles al aumentar zoom o tamaño de texto?
