---
type: api
name: rest-query
---

# Consulta REST

## Definición

Una consulta REST expone una operación de lectura mediante HTTP sin solicitar una modificación del estado del recurso consultado.

## Criterios

### Recurso y método

- ¿Cuál es la URI del recurso o colección?
- ¿Qué variables de ruta admite la URI?
- ¿Qué método HTTP representa la consulta?
- ¿La operación conserva semántica segura y no solicita cambios de estado del servidor?
- ¿La operación es idempotente?
- Si se soporta `HEAD`, ¿qué metadatos debe devolver respecto de `GET`?

### Parámetros

- ¿Qué parámetros de consulta se admiten?
- ¿Qué tipo tiene cada parámetro?
- ¿Qué parámetros son obligatorios?
- ¿Qué parámetros pueden repetirse?
- ¿Qué valor predeterminado tiene cada parámetro omitido?
- ¿Qué rango o formato debe cumplir cada parámetro?
- ¿Cómo se representa ausencia o `null`?
- ¿Cómo se codifican colecciones o filtros compuestos?

### Representación solicitada

- ¿Qué media types se aceptan mediante negociación de contenido?
- ¿Qué debe ocurrir cuando no puede producirse una representación aceptable?
- ¿Qué mecanismo de autenticación se requiere?
- ¿Qué reglas de autorización limitan recursos, registros o campos visibles?

### Respuesta exitosa

- ¿Qué código de estado representa una consulta exitosa?
- ¿Qué media type tiene el cuerpo de respuesta?
- ¿Qué esquema debe cumplir el cuerpo?
- ¿Qué respuesta representa una consulta válida sin resultados?
- ¿Qué encabezados forman parte del contrato público de la API?
- ¿La compresión de contenido forma parte de un requisito observable de interoperabilidad?

### Filtros, orden y proyección

- ¿Qué campos pueden filtrarse?
- ¿Qué operadores admite cada filtro?
- ¿Cómo se combinan filtros repetidos o grupos lógicos?
- ¿Qué campos pueden utilizarse para ordenar?
- ¿Se permiten varias claves de orden?
- ¿Cómo se ordenan valores `null`?
- ¿Qué criterio de desempate garantiza orden estable?
- ¿Puede solicitarse un subconjunto de campos?
- ¿Qué debe ocurrir si se solicita un campo que el sujeto no puede consultar?

### Paginación

- ¿Se utiliza paginación por página y offset, cursor o token de continuación?
- ¿Cuál es el tamaño predeterminado de página?
- ¿Cuál es el tamaño máximo de página?
- ¿Cómo se representa la página o cursor siguiente?
- ¿Cómo se representa la página o cursor anterior cuando corresponde?
- ¿Se devuelve el total de elementos?
- ¿El total es exacto o aproximado?
- ¿Qué debe ocurrir con una página fuera de rango?
- ¿Qué debe ocurrir con un cursor inválido o expirado?
- ¿Qué garantías existen cuando los datos cambian entre páginas?

### Caché y solicitudes condicionales

- ¿La respuesta puede almacenarse en caché?
- ¿Qué directivas de caché forman parte del contrato?
- ¿La respuesta incluye una entidad de versión como `ETag`?
- ¿La respuesta incluye `Last-Modified`?
- ¿Se admiten solicitudes condicionales mediante `If-None-Match`?
- ¿Se admiten solicitudes condicionales mediante `If-Modified-Since`?
- ¿Qué condición produce una respuesta `304 Not Modified`?
- ¿Qué datos de autenticación o variación deben separar entradas de caché?

### CORS

- ¿La API permite solicitudes cross-origin desde navegador?
- ¿Qué orígenes se permiten?
- ¿Se permiten credenciales cross-origin?
- ¿Qué métodos y encabezados están permitidos en preflight?
- ¿Qué encabezados de respuesta deben exponerse al código del origen solicitante?
- ¿La duración de caché del preflight forma parte de la política?
- ¿La respuesta debe variar por `Origin` cuando el origen permitido cambia dinámicamente?

### Errores

- ¿Qué condición produce `400 Bad Request`?
- ¿Qué condición produce `401 Unauthorized`?
- ¿Qué condición produce `403 Forbidden`?
- ¿Qué condición produce `404 Not Found`?
- ¿Qué condición produce `406 Not Acceptable`?
- ¿Qué condición produce `416 Range Not Satisfiable` cuando se admite semántica de rangos?
- ¿Qué condición produce `429 Too Many Requests`?
- ¿Qué condición produce `500 Internal Server Error`?
- ¿Qué condición produce `503 Service Unavailable`?
- ¿Qué formato uniforme representa los errores?
- ¿Qué campos estables identifican tipo, código, detalle y ubicación del error?
- ¿Los errores de parámetros identifican el parámetro y un código verificable?
- ¿Las respuestas que admiten reintento incluyen información de cuándo puede reintentarse?
