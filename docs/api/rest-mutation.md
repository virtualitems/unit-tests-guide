# Operaciones de mutación

- ¿Qué URL debe recibir la petición?

## Inputs

- ¿Qué método HTTP debe utilizarse en la petición?
- ¿Qué datos deben recibirse en la petición?
    - ¿Debe recibirse un token de autenticación?
    - ¿Debe recibirse un token CSRF?
- ¿En qué formato deben recibirse los datos de la petición?
    - ¿Qué estructura deben tener los datos de la petición?

## Outputs

- ¿Qué headers de CORS deben incluirse?
    - ¿Qué métodos HTTP deben permitirse?
    - ¿Qué cabeceras deben permitirse?
    - ¿Qué orígenes deben permitirse?
- ¿Qué datos deben devolverse en la respuesta?
- ¿En qué formato deben devolverse los datos de la respuesta?
    - ¿Qué estructura deben tener los datos de la respuesta?
- ¿A qué URL debe redirse al usuario al terminar la operación?
    - ¿Qué metodo HTTP debe utilizarse al redirigir al usuario?

## Errores

- ¿Qué debe suceder al no estar autenticado?
- ¿Qué debe suceder al no tener permisos para realizar la operación?
- ¿Qué debe suceder al no encontrar los datos?
- ¿Qué debe suceder al no poder realizar la operación?

## Posibles códigos de estado

- **200 OK:** (Respuesta exitosa con contenido)
- **201 Created:** (Recurso creado exitosamente)
- **202 Accepted:** (Solicitud aceptada para procesamiento asincrónico)
- **204 No Content:** (Operación exitosa sin contenido devuelto)
- **206 Partial Content:** (Respuesta parcial de una descarga)
- **304 Not Modified:** Recurso no modificado desde la última solicitud
- **307 Temporary Redirect:** Redirección temporal sin cambiar el método HTTP
- **308 Permanent Redirect:** Redirección permanente sin cambiar el método HTTP
- **400 Bad Request:** Solicitud incorrecta o malformada
- **401 Unauthorized:** Usuario no autenticado
- **403 Forbidden:** Usiario autenticado pero sin permisos
- **404 Not Found:** Recurso no encontrado
- **405 Method Not Allowed:** El método HTTP no es permitido para el recurso
- **406 Not Acceptable:** El recurso no puede ser devuelto en el formato del header Accept
- **409 Conflict:** Conflicto con el estado actual del recurso
- **415 Unsupported Media Type:** El tipo de contenido en el header Content-Type no es soportado
- **429 Too Many Requests:** Demasiadas solicitudes en un corto periodo de tiempo
- **500 Internal Server Error:** Error interno del servidor
- **501 Not Implemented:** Operación no soportada por el servidor
- **503 Service Unavailable:** Servicio no disponible temporalmente