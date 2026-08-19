---
type: operation
name: export
---

# Exportación

## Definición

Una exportación es una operación que produce una representación de información para utilizarla fuera del ámbito que la origina.

## Criterios

### Selección

- ¿Qué información debe incluir la exportación?
- ¿Qué filtros determinan qué registros forman parte de la exportación?
- ¿Qué reglas de autorización limitan la información exportable?
- ¿Qué campos deben excluirse por privacidad o seguridad?
- ¿El orden de los registros forma parte del contrato?

### Representación

- ¿En qué formato se produce la exportación?
- ¿Qué versión del formato se utiliza?
- ¿Qué codificación se utiliza?
- ¿Qué esquema, columnas o estructura debe tener el resultado?
- ¿Qué representación se utiliza para `null`, fechas, números y booleanos?
- ¿Qué locale y zona horaria se utilizan cuando la representación los requiere?

### Consistencia

- ¿La exportación representa una instantánea consistente de los datos?
- ¿Qué instante o versión determina los datos incluidos?
- ¿Qué debe ocurrir si los datos cambian mientras se genera la exportación?

### Límites y ejecución

- ¿Existe un máximo de registros exportables?
- ¿Existe un máximo de tamaño?
- ¿La exportación se produce de forma sincrónica o asíncrona?
- Si es asíncrona, ¿qué estado permite observar su progreso?
- ¿Qué debe ocurrir si una parte de la exportación falla?
- ¿Puede producirse un archivo parcial?

### Archivo y entrega

- ¿Qué nombre debe tener el archivo resultante?
- ¿Qué extensión debe tener?
- ¿Debe comprimirse?
- ¿Debe cifrarse?
- ¿Durante cuánto tiempo permanece disponible?
- ¿Quién puede descargarlo después de generarlo?
- ¿Debe registrarse quién solicitó o descargó la exportación?
