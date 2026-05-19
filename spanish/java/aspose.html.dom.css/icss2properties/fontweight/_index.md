---
title: "ICSS2Properties.FontWeight"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSS2Properties. La propiedad font-weight especifica el grosor de la fuente. Los valores tienen los siguientes significados"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/fontweight/
---
## ICSS2Properties.FontWeight property

La propiedad 'font-weight' especifica el grosor de la fuente. Los valores tienen los siguientes significados:

100 a 900 - Estos valores forman una secuencia ordenada, donde cada número indica un grosor que es al menos tan oscuro como el anterior. normal - Igual que '400'. bold - Igual que '700'. bolder - Especifica el siguiente grosor que se asigna a una fuente que es más oscura que la heredada. Si no existe tal grosor, simplemente resulta en el siguiente valor numérico más oscuro (y la fuente permanece sin cambios), a menos que el valor heredado sea '900', en cuyo caso el grosor resultante también es '900'. lighter - Especifica el siguiente grosor que se asigna a una fuente que es más clara que la heredada. Si no existe tal grosor, simplemente resulta en el siguiente valor numérico más claro (y la fuente permanece sin cambios), a menos que el valor heredado sea '100', en cuyo caso el grosor resultante también es '100'.

```java
public String FontWeight { get; set; }
```

### Valor de retorno

propiedad font-weight

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
