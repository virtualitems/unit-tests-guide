# Contratos de criterios de aceptación

Esta guía contiene preguntas para definir contratos de criterios de aceptación sobre valores, reglas de negocio y operaciones de software.

Un contrato registra decisiones verificables antes de implementar el software. La implementación utiliza esas decisiones como criterios de comportamiento. Las pruebas automatizadas implementan después los mismos criterios para comprobar que el software satisface el contrato.

El flujo de trabajo es:

1. Identificar los valores, reglas y operaciones que participan en el comportamiento que se va a implementar.
2. Responder las preguntas aplicables de esta guía y registrar las respuestas como criterios de aceptación.
3. Implementar el software conforme al contrato resultante.
4. Convertir los criterios del contrato en pruebas automatizadas sin agregar requisitos que no hayan sido definidos previamente.

Las preguntas de la guía deben describir decisiones observables. Un criterio debe indicar el dato, estado, condición, límite, resultado o efecto que permita distinguir una implementación válida de una inválida. Los detalles de framework, librería, almacenamiento o transporte solo forman parte del contrato cuando el producto exige ese detalle de forma explícita.

## Valores

- [Texto](./docs/value/text.md)
- [Número](./docs/value/number.md)
- [Booleano](./docs/value/boolean.md)
- [Fecha y hora](./docs/value/date.md)
- [Colección](./docs/value/collection.md)
- [Archivo](./docs/value/file.md)

## Reglas de negocio

- [Restricción](./docs/rule/restriction.md)
- [Validación](./docs/rule/validation.md)
- [Elegibilidad](./docs/rule/eligibility.md)
- [Autorización](./docs/rule/authorization.md)
- [Cálculo](./docs/rule/calculation.md)
- [Clasificación](./docs/rule/classification.md)
- [Decisión](./docs/rule/decision.md)
- [Derivación](./docs/rule/derivation.md)
- [Obligación](./docs/rule/obligation.md)
- [Regla temporal](./docs/rule/temporal.md)
- [Umbral](./docs/rule/threshold.md)
- [Dependencia](./docs/rule/dependency.md)

## Operaciones

- [Creación](./docs/operation/creation.md)
- [Modificación](./docs/operation/modification.md)
- [Eliminación](./docs/operation/deletion.md)
- [Consulta](./docs/operation/query.md)
- [Transición de estado](./docs/operation/state-transition.md)
- [Cálculo](./docs/operation/calculation.md)
- [Proceso](./docs/operation/process.md)
- [Asignación](./docs/operation/assignment.md)
- [Desasignación](./docs/operation/unassignment.md)
- [Transferencia](./docs/operation/transfer.md)
- [Notificación](./docs/operation/notification.md)
- [Importación](./docs/operation/import.md)
- [Exportación](./docs/operation/export.md)

Los documentos de `docs/ui/` y `docs/api/` se mantienen como material contractual adicional. Su incorporación al índice principal depende de definir si estas capas forman parte del modelo general de la guía o si deben tratarse como perfiles técnicos de las operaciones de dominio.
