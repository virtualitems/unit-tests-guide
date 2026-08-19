---
type: value
name: date
---

# Fecha y hora

## Definición

Un valor temporal representa una fecha civil, una hora, una fecha y hora local, un instante, una duración o un intervalo.

## Criterios

### Tipo temporal

- ¿El valor representa una fecha civil?
- ¿El valor representa una hora del día?
- ¿El valor representa una fecha y hora local?
- ¿El valor representa un instante absoluto?
- ¿El valor representa una duración?
- ¿El valor representa un intervalo?

### Presencia

- ¿Puede estar ausente?
- ¿Puede ser `null`?
- ¿Existe un valor predeterminado?
- Si el valor predeterminado depende de la hora actual, ¿en qué momento exacto se evalúa?

### Componentes

- ¿Qué calendario se utiliza?
- ¿Debe contener año?
- ¿Debe contener mes?
- ¿Debe contener día?
- ¿Debe contener hora?
- ¿Debe contener minuto?
- ¿Debe contener segundo?
- ¿Se permiten fracciones de segundo?
- ¿Qué precisión máxima tienen las fracciones de segundo?
- ¿Se permiten fechas parciales?

### Zona horaria y offset

- ¿El valor requiere un offset UTC explícito?
- ¿El valor requiere un identificador de zona horaria?
- ¿Las comparaciones se realizan como instantes absolutos o como valores locales?
- ¿La salida debe normalizarse a UTC?
- ¿Debe preservarse el offset recibido?
- ¿Qué zona horaria utiliza una regla de negocio cuando no viene incluida en el valor?
- ¿Qué debe ocurrir si la zona horaria indicada no existe o no está disponible?
- ¿Qué debe ocurrir con una hora local inexistente durante un cambio de horario?
- ¿Qué debe ocurrir con una hora local ambigua durante un cambio de horario?

### Formato

- ¿Cuál es el formato canónico de serialización?
- ¿Qué formatos de entrada se aceptan?
- ¿La representación debe incluir zona horaria u offset?
- ¿Se aceptan segundos intercalares?

### Rango

- ¿Existe un valor mínimo?
- ¿El valor mínimo es inclusivo o exclusivo?
- ¿Existe un valor máximo?
- ¿El valor máximo es inclusivo o exclusivo?

### Cálculo temporal

- ¿Qué unidad se utiliza al calcular duraciones?
- ¿Cómo se calcula una duración que atraviesa un cambio de offset?
- ¿Cómo se calcula una duración expresada en meses o años de distinta longitud?
- ¿Qué regla se aplica a fechas como el 29 de febrero al sumar años?
