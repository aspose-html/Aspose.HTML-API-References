---
title: "ICSSRule.ParentRule"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSSRule. Si esta regla está contenida dentro de otra regla, por ejemplo una regla de estilo dentro de un bloque de medios, esta es la regla contenedora. Si esta regla no está anidada dentro de ninguna otra regla, devuelve null."
type: docs

url: /es/java/com.aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

Si esta regla está contenida dentro de otra regla (p. ej., una regla de estilo dentro de un bloque @media), esta es la regla contenedora. Si esta regla no está anidada dentro de ninguna otra regla, devuelve null.

```java
public ICSSRule ParentRule { get; }
```

### Property Value

Un [`CSSRule`](../) que es el tipo de las reglas contenedoras. Si la regla actual está dentro de una consulta de medios, devolvería [`CSSMediaRule`](../../icssmediarule/). De lo contrario, devuelve null.

### Ver también

* interface [ICSSRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
