---
type: operation
name: transfer
---

# Transferencia

## Definición

Una transferencia es una operación que mueve un recurso, valor, propiedad, responsabilidad o relación desde un origen hacia un destino.

## Criterios

### Transferido

- ¿Qué recurso, cantidad, derecho, propiedad, responsabilidad o relación se transfiere?
- ¿La transferencia es total o parcial?
- Si es cuantitativa, ¿qué cantidad se transfiere?
- ¿Qué unidad utiliza la cantidad?

### Origen y destino

- ¿Cuál es el origen?
- ¿Cuál es el destino?
- ¿Se permite que origen y destino sean el mismo elemento?
- ¿Qué resultado produce una transferencia al mismo origen?

### Precondiciones

- ¿Qué condiciones debe cumplir el origen?
- ¿Qué condiciones debe cumplir el destino?
- ¿Debe existir saldo o capacidad suficiente en el origen?
- ¿Existe una capacidad máxima en el destino?
- ¿Qué reglas de autorización deben cumplirse?

### Cálculo

- ¿Existe una comisión?
- ¿Cómo se calcula la comisión?
- ¿Existe conversión entre unidades o monedas?
- ¿Qué tasa de conversión se utiliza?
- ¿Qué regla de redondeo se aplica?

### Resultado e invariantes

- ¿Qué cambio debe producirse en el origen?
- ¿Qué cambio debe producirse en el destino?
- ¿Qué invariante de conservación debe cumplirse antes y después?
- ¿La disminución del origen y el aumento del destino son atómicos?
- ¿Qué debe ocurrir si falla una parte de la transferencia?

### Repetición, concurrencia y reversión

- ¿La operación debe ser idempotente ante reintentos?
- ¿Qué identificador distingue una transferencia lógica de otra?
- ¿Cómo se controla la concurrencia sobre origen y destino?
- ¿Puede revertirse la transferencia?
- ¿La reversión se representa como una nueva transferencia o como restauración del estado anterior?
- ¿Qué historial o evidencia debe conservarse?
