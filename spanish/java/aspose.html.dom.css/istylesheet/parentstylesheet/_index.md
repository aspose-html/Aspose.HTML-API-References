---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad IStyleSheet. Para los lenguajes de hojas de estilo que admiten el concepto de inclusión de hojas de estilo, este atributo representa la hoja de estilo que incluye, si existe. Si la hoja de estilo es una hoja de estilo de nivel superior o el lenguaje de hojas de estilo no admite la inclusión, el valor de este atributo es null."
type: docs

url: /es/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

Para los lenguajes de hojas de estilo que admiten el concepto de inclusión de hojas de estilo, este atributo representa la hoja de estilo que incluye, si existe. Si la hoja de estilo es una hoja de estilo de nivel superior, o el lenguaje de hojas de estilo no admite la inclusión, el valor de este atributo es null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

El atributo parentStyleSheet debe devolver la hoja de estilo CSS padre [`CSS style sheet`](../../icssstylesheet/).

## Observaciones

Esta propiedad devuelve null si la hoja de estilo actual es una hoja de estilo de nivel superior o si la inclusión de hojas de estilo no está soportada.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### Ver también

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
