---
type: operation
name: creation
---

# Creación

## Definición

Una creación es una operación que hace existir un nuevo elemento.

## Criterios

### Elemento

- ¿Qué tipo de elemento se crea?
- ¿Qué identifica de forma única al elemento creado?
- ¿Quién genera el identificador?

### Entrada

- ¿Qué datos se utilizan para crear el elemento?
- ¿Qué datos son obligatorios?
- ¿Qué datos son opcionales?
- ¿Qué valores predeterminados se aplican a datos omitidos?
- ¿Qué datos pueden derivarse de otros datos o del contexto?

### Precondiciones

- ¿Qué condiciones deben cumplirse antes de crear el elemento?
- ¿Qué reglas de validación debe cumplir la entrada?
- ¿Qué reglas de autorización deben cumplirse?
- ¿Qué dependencias deben existir?
- ¿Qué debe ocurrir si ya existe un elemento con la misma identidad o clave de unicidad?

### Resultado

- ¿Qué datos debe tener el elemento creado?
- ¿Cuál es su estado inicial?
- ¿Qué relaciones deben existir después de la creación?
- ¿Qué datos derivados deben calcularse durante la creación?
- ¿Qué timestamp o versión forma parte del resultado?

### Atomicidad y repetición

- ¿La creación es atómica con sus relaciones y efectos asociados?
- ¿Qué debe ocurrir si falla una parte de la creación?
- ¿Repetir la misma solicitud lógica puede crear más de un elemento?
- ¿Existe una clave de idempotencia o identidad que impida duplicados por reintentos?

### Concurrencia y efectos

- ¿Qué debe ocurrir si dos creaciones concurrentes compiten por una clave única?
- ¿Qué efectos secundarios forman parte del contrato?
- ¿Qué debe ocurrir si un efecto secundario falla después de crear el elemento?
