---
type: value
name: text
---

# Texto

## Definición

Un texto es una secuencia de caracteres utilizada para representar información mediante símbolos, palabras, identificadores u otras formas de contenido textual.

## Criterios

### Presencia

- ¿Puede estar ausente?
- ¿Puede ser `null`?
- ¿Puede ser una cadena vacía?
- ¿Puede contener únicamente espacios?
- ¿Ausencia, `null`, cadena vacía y espacios representan estados distintos?
- ¿Existe un valor predeterminado?
- ¿Cómo se obtiene el valor predeterminado cuando no es constante?

### Caracteres

- ¿Qué repertorio de caracteres se admite?
- ¿Qué caracteres deben rechazarse?
- ¿Se permiten caracteres de control?
- ¿Se permiten caracteres invisibles?
- ¿Se permiten saltos de línea?
- ¿Se permiten separadores Unicode distintos del espacio común?
- ¿Qué codificación debe utilizarse al intercambiar o almacenar el texto cuando forme parte del contrato?

### Normalización

- ¿Debe aplicarse una forma de normalización Unicode antes de validar, comparar o almacenar el texto?
- ¿Deben conservarse los espacios iniciales?
- ¿Deben conservarse los espacios finales?
- ¿Deben conservarse las secuencias de espacios internos?
- ¿Deben normalizarse los saltos de línea?
- ¿Debe transformarse el uso de mayúsculas y minúsculas?
- ¿La transformación de mayúsculas y minúsculas depende de un locale determinado?

### Longitud

- ¿Cómo se mide la longitud: bytes, puntos de código Unicode o caracteres percibidos por el usuario?
- ¿Cuál es la longitud mínima permitida?
- ¿El límite mínimo se evalúa antes o después de normalizar el texto?
- ¿Cuál es la longitud máxima permitida?
- ¿El límite máximo se evalúa antes o después de normalizar el texto?

### Comparación

- ¿Las mayúsculas y minúsculas se consideran diferentes?
- ¿Los acentos y otras marcas diacríticas se consideran diferentes?
- ¿La comparación depende de un locale determinado?
- ¿La comparación se realiza sobre el texto original o sobre una representación normalizada?
- ¿Qué regla determina que dos textos son equivalentes?

### Contenido

- ¿Existe contenido que deba rechazarse aunque utilice caracteres permitidos?
- ¿Existe contenido reservado que tenga un significado especial?
- ¿Se permite texto compuesto solo por signos de puntuación, símbolos o caracteres equivalentes?
- ¿Se permite contenido bidireccional y qué restricciones debe cumplir cuando tenga impacto de seguridad o representación?

### Formato

- ¿Debe cumplir un formato concreto?
- ¿Qué especificación o patrón define el formato?
- ¿La coincidencia con el formato debe abarcar el valor completo?
- ¿Qué partes del formato son obligatorias?
- ¿Qué partes del formato son opcionales?
- ¿Existe una representación canónica para el valor válido?

### Contraseña

- ¿Qué longitud mínima exige la política de contraseña?
- ¿Cuál es la longitud máxima aceptada?
- ¿Se aceptan espacios?
- ¿Se aceptan caracteres Unicode?
- ¿La contraseña se verifica completa sin truncamiento silencioso?
- ¿Debe rechazarse una contraseña incluida en una lista de valores comunes, esperables o comprometidos?
- ¿Existe una regla de composición de caracteres exigida por una política concreta?
- ¿Existe una regla de cambio periódico exigida por una política concreta?
- ¿Qué normalización se aplica antes de verificar la contraseña, si se aplica alguna?

### Formatos específicos

- Para una dirección de correo electrónico, ¿qué sintaxis se admite y qué normalización se aplica antes de comparar o almacenar?
- Para una ruta de archivo, ¿qué plataforma o sintaxis determina qué rutas son válidas?
- Para JSON, ¿se valida únicamente la sintaxis o también un esquema concreto?
- Para un teléfono, ¿qué plan de numeración, país o representación canónica se utiliza?
- Para un slug, ¿qué caracteres, separadores, normalización y reglas de unicidad se aplican?
- Para una URI o URL, ¿qué componentes y esquemas se permiten?
- Para un UUID, ¿qué versiones y representación canónica se permiten?
- Para XML, ¿se valida únicamente la sintaxis o también un esquema, namespaces u otras restricciones estructurales?
