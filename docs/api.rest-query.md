# Consulta de datos

- ¿Qué URL debe recibir la petición?

## Inputs

- ¿Qué datos deben recibirse en la petición?
    - ¿Debe recibirse un token de autenticación?
    - ¿Debe recibirse un token CSRF?
- ¿En qué formato deben recibirse los datos de la petición?

## Outputs

- ¿Qué headers de CORS deben incluirse?
    - ¿Qué métodos HTTP deben permitirse?
    - ¿Qué cabeceras deben permitirse?
    - ¿Qué orígenes deben permitirse?
- ¿Qué codificación debe tener la respuesta?
    - ¿El header Content-Length debe ser incluido en la respuesta?
    - ¿El header Transfer-Encoding debe ser incluido en la respuesta?
    - ¿Qué valor debe tener el header Content-Type?
- ¿Debe tener funcionalidad de paginación?
    - ¿Cuántos datos deben mostrarse por página?
- ¿Debe tener funcionalidad de filtro?
    - ¿A qué datos se les debe aplicar el filtro?
- ¿Debe tener funcionalidad de ordenamiento?
    - ¿A qué datos se les debe aplicar el ordenamiento?
    - ¿En qué orden deben ubicarse los datos?

## Errores

- ¿Qué debe suceder al no estar autenticado?
- ¿Qué debe suceder al no tener permisos para realizar la operación?
- ¿Qué debe suceder al no encontrar los datos?