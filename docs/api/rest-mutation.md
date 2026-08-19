---
type: api
name: rest-mutation
---

# Mutación REST

## Definición

Una mutación REST expone mediante HTTP una operación que crea, modifica, elimina o cambia el estado observable de un recurso.

## Criterios

### Recurso y método

- ¿Cuál es la URI del recurso o colección?
- ¿Qué variables de ruta admite la URI?
- ¿Qué método HTTP representa la operación?
- ¿La semántica de creación, reemplazo, modificación parcial o eliminación coincide con el método elegido?
- ¿La operación debe ser idempotente?

### Entrada

- ¿Qué datos recibe la solicitud?
- ¿Qué media type utiliza el cuerpo?
- ¿Qué esquema debe cumplir el cuerpo?
- ¿Qué campos son obligatorios?
- ¿Qué campos son opcionales?
- ¿Qué significa omitir un campo?
- ¿Qué significa enviar `null`?
- ¿Qué encabezados de aplicación son obligatorios?
- ¿Qué mecanismo de autenticación se requiere?
- ¿Qué reglas de autorización deben cumplirse?
- ¿La operación requiere protección CSRF según el modelo de credenciales utilizado?

### Precondiciones y concurrencia

- ¿La operación utiliza una versión o `ETag` para detectar cambios concurrentes?
- ¿El cliente debe enviar `If-Match` para modificar o eliminar una versión concreta?
- ¿Se utiliza `If-None-Match` para una creación condicional?
- ¿Qué debe ocurrir cuando la versión del recurso no satisface la precondición enviada por el cliente?
- ¿Qué debe ocurrir cuando el estado actual del recurso impide completar la operación?
- ¿Qué estado debe preservarse cuando falla una precondición?

### Idempotencia y reintentos

- ¿Puede el cliente repetir la solicitud después de un timeout sin duplicar el efecto?
- Si una operación `POST` necesita idempotencia, ¿qué clave identifica el intento lógico?
- ¿Durante cuánto tiempo conserva efecto la clave de idempotencia?
- ¿Qué respuesta produce una repetición con la misma clave y el mismo contenido?
- ¿Qué debe ocurrir si se reutiliza la misma clave con contenido distinto?

### Respuesta exitosa

- ¿Qué condición produce `200 OK`?
- ¿Qué condición produce `201 Created`?
- Si se crea un recurso, ¿qué URI se devuelve en `Location`?
- ¿Qué condición produce `202 Accepted`?
- Si el procesamiento es asíncrono, ¿qué recurso o estado permite observar su progreso?
- ¿Qué condición produce `204 No Content`?
- Si se utiliza `204`, ¿la respuesta carece de cuerpo?
- ¿La respuesta devuelve la representación actual del recurso, un identificador, el resultado de la operación o ningún contenido?
- ¿Qué media type y esquema tiene el cuerpo cuando existe?
- ¿La respuesta devuelve una versión o `ETag` del estado resultante?

### Atomicidad y efectos

- ¿La mutación es atómica?
- ¿Puede existir éxito parcial?
- Si existe éxito parcial, ¿qué unidades pueden fallar de forma independiente?
- ¿Cómo se representa el resultado parcial?
- ¿Qué efectos secundarios forman parte del contrato?
- ¿Qué debe revertirse cuando un efecto secundario falla?

### CORS

- ¿La API permite solicitudes cross-origin desde navegador?
- ¿Qué orígenes se permiten?
- ¿Qué métodos se permiten?
- ¿Qué encabezados de solicitud se permiten?
- ¿Se permiten credenciales cross-origin?
- Cuando se permiten credenciales, ¿qué origen explícito se devuelve en lugar de un comodín?
- ¿Qué encabezados de respuesta deben exponerse?
- ¿La duración de caché del preflight forma parte de la política?
- ¿La respuesta debe variar por `Origin` cuando el origen permitido cambia dinámicamente?

### Errores

- ¿Qué condición produce `400 Bad Request`?
- ¿Qué condición produce `401 Unauthorized`?
- ¿Qué condición produce `403 Forbidden`?
- ¿Qué condición produce `404 Not Found`?
- ¿Qué condición produce `405 Method Not Allowed`?
- Cuando se utiliza `405`, ¿la respuesta indica los métodos permitidos?
- ¿Qué condición produce `406 Not Acceptable`?
- ¿Qué condición produce `409 Conflict`?
- ¿Qué condición produce `412 Precondition Failed`?
- ¿Qué condición produce `415 Unsupported Media Type`?
- ¿La API utiliza `422 Unprocessable Content` para contenido sintácticamente procesable pero semánticamente inválido?
- Si utiliza `422`, ¿qué condición exacta lo distingue de `400` y `409`?
- ¿Qué condición produce `429 Too Many Requests`?
- ¿Qué condición produce `500 Internal Server Error`?
- ¿Qué condición produce `503 Service Unavailable`?
- ¿Qué formato uniforme representa los errores?
- ¿Qué campos estables identifican tipo, código, detalle y ubicación del error?
- ¿Los errores de validación identifican campo o ruta y un código verificable?
- ¿Las respuestas que admiten reintento indican cuándo puede realizarse?

### Redirección

- Si la operación forma parte de navegación web y termina con una redirección, ¿a qué URI redirige?
- ¿Qué código de redirección se utiliza?
- ¿La redirección debe conservar o cambiar el método de la solicitud posterior?
