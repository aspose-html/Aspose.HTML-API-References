---
title: "IStyleSheet.OwnerNode"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad IStyleSheet. El nodo que asocia esta hoja de estilo con el documento. Para HTML puede ser el elemento LINK o STYLE correspondiente. Para XML puede ser la instrucción de procesamiento de enlace. Para hojas de estilo que son incluidas por otras hojas de estilo el valor de este atributo es null"
type: docs

url: /es/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

El nodo que asocia esta hoja de estilo con el documento. Para HTML, puede ser el elemento LINK o STYLE correspondiente. Para XML, puede ser la instrucción de procesamiento de enlace. Para hojas de estilo que son incluidas por otras hojas de estilo, el valor de este atributo es null.

```java
public Node OwnerNode { get; }
```

### Property Value

El atributo ownerNode debe devolver el nodo propietario.

## Observaciones

Para hojas de estilo que son incluidas por otras hojas de estilo, como con @import, el valor de esta propiedad es null.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### Ver también

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
