---
type: value
name: file
---

# Archivo

## Definición

Un archivo es una unidad identificable de información que contiene datos y puede conservarse o transferirse como una unidad.

## Criterios

### Presencia

- ¿Puede estar ausente?
- ¿Puede ser `null`?
- ¿Puede tener tamaño cero?
- ¿Existe un archivo predeterminado?

### Tipo y contenido

- ¿Qué tipos de contenido se aceptan?
- ¿Qué extensiones se aceptan?
- ¿El tipo se determina por la extensión, el MIME declarado, la firma del contenido o una combinación de estos datos?
- ¿Qué debe ocurrir cuando la extensión, el MIME declarado y el contenido real no coinciden?
- ¿Qué debe ocurrir si el archivo está truncado o corrupto?
- ¿Qué codificación se exige para archivos de texto?

### Tamaño

- ¿Existe un tamaño mínimo?
- ¿Existe un tamaño máximo?
- ¿En qué unidad se expresan los límites de tamaño?

### Nombre

- ¿Debe preservarse el nombre original?
- ¿El nombre original se conserva únicamente como metadato?
- ¿Qué caracteres se permiten en el nombre?
- ¿Qué caracteres o secuencias deben rechazarse por representar rutas o nombres reservados?
- ¿Cuál es la longitud máxima del nombre?
- ¿Cómo se mide la longitud del nombre?
- ¿Puede omitirse la extensión?
- ¿Se permiten extensiones múltiples o dobles?

### Integridad y seguridad

- ¿Debe verificarse la integridad del archivo mediante un hash o checksum?
- ¿Qué algoritmo se utiliza cuando se exige verificación de integridad?
- ¿Debe analizarse el archivo para detectar malware o contenido activo?
- ¿Se permiten archivos comprimidos?
- ¿Cuál es el tamaño máximo permitido después de descomprimir?
- ¿Cuál es la cantidad máxima de entradas de un archivo comprimido?
- ¿Cuál es la profundidad máxima de archivos comprimidos anidados?

### CSV y datos tabulares

- ¿Qué delimitador se utiliza?
- ¿Qué carácter delimita valores entre comillas?
- ¿Cómo se escapan las comillas dentro de un valor?
- ¿Existe una fila de encabezados?
- ¿Qué columnas son obligatorias?
- ¿Qué columnas son opcionales?
- ¿Se permiten columnas adicionales?
- ¿El orden de las columnas tiene significado?
- ¿Cómo se representan valores vacíos y `null`?
- ¿Qué codificación de texto se utiliza?
- ¿Qué separador de línea se acepta?

### Imagen

- ¿Qué formatos de imagen se permiten?
- ¿Cuál es el ancho mínimo y máximo?
- ¿Cuál es el alto mínimo y máximo?
- ¿Existe una relación de aspecto permitida?
- ¿Se permite contenido animado?
- ¿Deben conservarse o eliminarse metadatos embebidos?

### Audio y video

- ¿Qué formatos o contenedores se permiten?
- ¿Qué codecs se permiten?
- ¿Existe una duración mínima?
- ¿Existe una duración máxima?
- ¿Existe un bitrate mínimo o máximo?
- ¿Qué debe ocurrir si el contenido no puede decodificarse con los formatos permitidos?
