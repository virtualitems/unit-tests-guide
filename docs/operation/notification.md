---
type: operation
name: notification
---

# Notificación

## Definición

Una notificación es una operación que comunica información a uno o más destinatarios mediante uno o varios canales.

## Criterios

### Activación

- ¿Qué evento o condición activa la notificación?
- ¿Puede el mismo evento activar más de una notificación?
- ¿Cómo se identifica un evento para evitar notificaciones duplicadas?

### Remitente y destinatarios

- ¿Quién figura como remitente u origen?
- ¿Cómo se determinan los destinatarios?
- ¿Puede existir más de un destinatario?
- ¿Qué debe ocurrir cuando un destinatario no puede resolverse?

### Canal

- ¿Qué canales se permiten?
- ¿Se envía por varios canales simultáneamente?
- ¿Existe prioridad entre canales?
- ¿Existe un canal alternativo cuando falla el principal?
- ¿Qué preferencias, consentimiento u opt-out deben respetarse por canal?

### Contenido

- ¿Qué plantilla se utiliza?
- ¿Qué versión de la plantilla se utiliza?
- ¿Qué datos se interpolan en la plantilla?
- ¿Qué debe ocurrir cuando falta un dato requerido por la plantilla?
- ¿Qué idioma o locale utiliza cada destinatario?
- ¿Qué zona horaria se utiliza para contenido temporal?
- ¿Qué datos sensibles pueden aparecer en asunto, vista previa, cuerpo o URL?

### Programación

- ¿El envío es inmediato o programado?
- ¿Existe una fecha de expiración después de la cual ya no debe enviarse?
- ¿Existen ventanas horarias en las que no debe enviarse?

### Entrega y fallos

- ¿Qué estados de entrega deben ser observables?
- ¿Cuántos reintentos se permiten?
- ¿Qué espera existe entre reintentos?
- ¿Cuándo deja de reintentarse una notificación?
- ¿Se admite éxito parcial al notificar a varios destinatarios?
- ¿Cómo se informa qué destinatarios recibieron o no recibieron la notificación?
- Si la notificación contiene un enlace de acción, ¿qué vigencia y autorización tiene?
