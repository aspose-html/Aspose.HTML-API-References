---
title: "ICSS2Properties.Speak"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "propiedad ICSS2Properties. Esta propiedad especifica si el texto se renderizará de forma auditiva y, de ser así, de qué manera, de manera algo análoga a la propiedad display. Los valores posibles son"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

Esta propiedad especifica si el texto se renderizará de forma auditiva y, de ser así, de qué manera (algo análoga a la propiedad ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) ). Los valores posibles son:

none - Suprime la renderización auditiva de modo que el elemento no requiera tiempo para renderizarse. Nota, sin embargo, que los descendientes pueden sobrescribir este valor y serán pronunciados. (Para asegurarse de suprimir la renderización de un elemento y sus descendientes, use la propiedad ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) ).normal - Utiliza reglas de pronunciación dependientes del idioma para renderizar un elemento y sus hijos. spell-out - Deletrea el texto letra por letra (útil para acrónimos y abreviaturas).

```java
public String Speak { get; set; }
```

### Valor de retorno

propiedad speak

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
