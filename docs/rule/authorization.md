---
type: rule
name: authorization
---

# Autorización

## Definición

Una regla de autorización determina si un sujeto puede realizar una acción sobre un recurso o dentro de un ámbito determinado.

## Criterios

### Sujeto

- ¿Qué sujeto solicita la acción?
- ¿El sujeto debe estar autenticado?
- ¿Qué nivel o mecanismo de autenticación es suficiente?
- ¿Qué atributos del sujeto participan en la decisión?

### Acción y recurso

- ¿Qué acción concreta se autoriza?
- ¿Sobre qué recurso o instancia se evalúa la autorización?
- ¿La autorización aplica al recurso completo o solo a determinados campos, relaciones o subrecursos?
- ¿Qué límites de tenant, organización o dominio de seguridad forman parte del alcance?

### Contexto

- ¿Qué atributos del recurso participan en la decisión?
- ¿Qué condiciones de tiempo participan en la decisión?
- ¿Qué condiciones de sesión, dispositivo, red o ubicación participan en la decisión cuando forman parte de la política?
- ¿Qué debe ocurrir cuando falta un atributo necesario para decidir?

### Política

- ¿La ausencia de una regla aplicable produce denegación?
- ¿Qué precedencia existe cuando una regla permite y otra deniega?
- ¿Existen permisos heredados?
- ¿Existen permisos delegados?
- ¿Existen permisos temporales?
- ¿Cuándo comienza y termina la vigencia de un permiso?
- ¿Qué evento revoca un permiso?
- ¿Cómo se preserva el aislamiento entre ámbitos de seguridad?

### Resultado

- ¿El resultado debe indicar únicamente permitido o denegado?
- ¿Debe incluir una razón o código verificable?
- ¿Una denegación debe ocultar la existencia del recurso?
