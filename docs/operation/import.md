---
type: operation
name: import
---

# Importación

## Definición

Una importación es una operación que incorpora información proveniente de una fuente externa al modelo interno del sistema.

## Criterios

### Origen y formato

- ¿Qué fuentes externas se admiten?
- ¿Qué formato se acepta?
- ¿Qué versión del formato se acepta?
- ¿Qué codificación se acepta?
- ¿Qué esquema debe cumplir la entrada?

### Mapeo

- ¿Cómo se mapea cada campo externo a un campo interno?
- ¿Qué campos externos son obligatorios?
- ¿Qué campos externos son opcionales?
- ¿Qué campos externos se ignoran?
- ¿Qué debe ocurrir con campos desconocidos o adicionales?
- ¿Cómo se transforman tipos o representaciones antes de incorporar los datos?

### Identidad y duplicados

- ¿Cómo se identifica que un registro importado ya existe?
- ¿Qué debe ocurrir cuando se encuentra un duplicado?
- ¿El duplicado se omite, actualiza, fusiona o produce error?
- ¿Reimportar el mismo contenido debe producir el mismo estado final?

### Validación

- ¿La validación se realiza sobre el archivo completo?
- ¿La validación se realiza sobre cada registro?
- ¿Qué debe ocurrir cuando un registro es inválido?
- ¿Un registro inválido hace fallar toda la importación?
- ¿Puede existir un resultado parcial?
- ¿Qué información debe incluir el reporte de errores?
- ¿Debe identificarse fila, campo, código y motivo del error?

### Ejecución

- ¿La importación es atómica?
- ¿Se procesa por lotes o por registro?
- ¿Existe rollback si falla una parte posterior?
- ¿El orden de los registros afecta el resultado?
- ¿Cómo se resuelven referencias entre registros de la misma importación?
- ¿Cómo se resuelven modificaciones concurrentes durante la importación?

### Límites y trazabilidad

- ¿Existe un máximo de registros?
- ¿Existe un máximo de tamaño?
- ¿Existe un máximo de duración de procesamiento?
- ¿Debe conservarse la procedencia de cada dato importado?
- ¿Debe conservarse el archivo fuente o su identificador?
- ¿Debe registrarse el momento de la importación?
- ¿Existe un modo de validación o simulación que no aplique cambios?
