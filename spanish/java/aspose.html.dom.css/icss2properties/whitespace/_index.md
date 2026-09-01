---
title: "ICSS2Properties.WhiteSpace"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSS2Properties. Esta propiedad declara cómo se maneja el espacio en blanco dentro del elemento. Los valores tienen los siguientes significados"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

Esta propiedad declara cómo se maneja el [espacio en blanco](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace) dentro del elemento. Los valores tienen los siguientes significados:

normal - Este valor indica a los agentes de usuario que colapsen secuencias de espacio en blanco y que rompan líneas según sea necesario para rellenar los contenedores de línea. Se pueden crear saltos de línea adicionales mediante ocurrencias de "\\A" en el contenido generado (p. ej., para el elemento BR en HTML). pre - Este valor evita que los agentes de usuario colapsen secuencias de espacio en blanco. Las líneas solo se rompen en los saltos de línea del origen, o en ocurrencias de "\\A" en el contenido generado. nowrap - Este valor colapsa el espacio en blanco como en 'normal', pero suprime los saltos de línea dentro del texto, excepto los creados por "\\A" en el contenido generado (p. ej., para el elemento BR en HTML).

```java
public String WhiteSpace { get; set; }
```

### Valor devuelto

propiedad white-space

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
