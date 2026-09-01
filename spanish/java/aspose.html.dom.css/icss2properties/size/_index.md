---
title: "ICSS2Properties.Size"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "propiedad ICSS2Properties. Esta propiedad especifica el tamaño y la orientación de un cuadro de página"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/size/
---
## ICSS2Properties.Size property

Esta propiedad especifica el tamaño y la orientación de un cuadro de página.

El tamaño de un cuadro de página puede ser \"absolute\" (tamaño fijo) o \"relative\" (escalable, es decir, ajustándose a los tamaños de hoja disponibles). Los cuadros de página relativos permiten a los agentes de usuario escalar un documento y aprovechar de manera óptima el tamaño objetivo.

Tres valores para la propiedad ['size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-size) crean un cuadro de página relativo:

auto - El cuadro de página se establecerá al tamaño y orientación de la hoja objetivo.landscape - Sobrescribe la orientación del objetivo. El cuadro de página tiene el mismo tamaño que el objetivo, y los lados más largos son horizontales.portrait - Sobrescribe la orientación del objetivo. El cuadro de página tiene el mismo tamaño que el objetivo, y los lados más cortos son horizontales.

```java
public String Size { get; set; }
```

### Valor devuelto

propiedad size

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
