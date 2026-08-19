---
type: operation
name: process
---

# Proceso

## Definición

Un proceso es una operación compuesta por acciones relacionadas que se ejecutan en un orden definido, de forma secuencial o paralela, para producir un resultado.

## Criterios

### Inicio

- ¿Qué evento inicia el proceso?
- ¿Qué datos o recursos necesita para comenzar?
- ¿Qué condiciones deben cumplirse antes de iniciarlo?
- ¿Cuál es el estado inicial?
- ¿Qué debe ocurrir si se intenta iniciar el mismo proceso más de una vez para la misma entidad?

### Pasos

- ¿Qué pasos componen el proceso?
- ¿Qué orden obligatorio existe entre los pasos?
- ¿Qué pasos pueden ejecutarse en paralelo?
- ¿Qué condiciones determinan ramas alternativas?
- ¿Cómo se sincronizan ramas paralelas?
- ¿Qué datos produce cada paso para los pasos posteriores?

### Esperas y tiempo

- ¿Qué eventos externos pueden dejar el proceso en espera?
- ¿Existe un timeout para cada espera?
- ¿Existe un timeout para el proceso completo?
- ¿Qué debe ocurrir cuando vence un timeout?

### Reintentos y fallos

- ¿Qué pasos pueden reintentarse?
- ¿Cuál es el límite de reintentos?
- ¿Qué pasos deben ser idempotentes para soportar reintentos?
- ¿Qué debe ocurrir cuando un paso falla?
- ¿Qué pasos completados deben compensarse cuando falla un paso posterior?
- ¿Qué debe ocurrir si una compensación falla?

### Control

- ¿El proceso puede pausarse?
- ¿El proceso puede reanudarse?
- ¿El proceso puede cancelarse?
- ¿Qué debe ocurrir con trabajos en curso al cancelar?
- ¿Cómo se evita que se ejecuten simultáneamente dos instancias incompatibles?

### Resultado

- ¿Qué progreso o estado intermedio debe ser observable?
- ¿Cuál es el criterio exacto de finalización exitosa?
- ¿Cuál es el criterio exacto de finalización fallida?
- ¿Qué estados terminales existen?
- ¿Qué efectos secundarios finales corresponden al éxito?
- ¿Qué efectos secundarios finales corresponden a la cancelación?
- ¿Qué efectos secundarios finales corresponden al error?
