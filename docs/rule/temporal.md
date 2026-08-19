---
type: rule
name: temporal
---

# Regla temporal

## Definición

Una regla temporal es una regla cuyo resultado depende de fechas, instantes, duraciones, intervalos, plazos, frecuencias o relaciones de orden en el tiempo.

## Criterios

### Referencia temporal

- ¿Qué fecha, instante o evento sirve como referencia?
- ¿Qué zona horaria se utiliza para interpretar la referencia?
- ¿La regla compara instantes absolutos o valores locales?
- ¿Qué precisión temporal utiliza la regla?

### Vigencia

- ¿Cuándo comienza a estar vigente la regla?
- ¿El inicio es inclusivo o exclusivo?
- ¿Cuándo termina su vigencia?
- ¿El final es inclusivo o exclusivo?
- ¿La regla tiene vigencia indefinida cuando no se especifica un final?

### Duraciones y plazos

- ¿Qué duración define el plazo?
- ¿En qué unidad se expresa la duración?
- ¿El cómputo utiliza tiempo continuo, días calendario o días hábiles?
- ¿Qué calendario de días hábiles se utiliza?
- ¿Qué ocurre cuando un plazo termina en un día no hábil?
- ¿Cómo se tratan cambios de zona horaria o de horario de verano dentro del plazo?

### Frecuencia

- ¿La regla se repite?
- ¿Con qué frecuencia se repite?
- ¿Existe una cantidad máxima de ocurrencias?
- ¿Existe una fecha de finalización de la recurrencia?
- ¿Qué ocurre cuando una ocurrencia coincide con una fecha no válida o inexistente?

### Orden y simultaneidad

- ¿Qué eventos deben ocurrir antes que otros?
- ¿Qué eventos pueden ocurrir simultáneamente?
- ¿Qué tolerancia temporal se admite al comparar eventos?
- ¿Cómo se resuelve un empate temporal cuando el orden afecta el resultado?

### Datos faltantes

- ¿Qué debe ocurrir cuando falta una fecha necesaria?
- ¿Qué debe ocurrir cuando una fecha es inválida o ambigua?
- ¿La hora actual debe proporcionarse como entrada para que la regla sea reproducible?
