---
title: "Interfaz IStyleSheet"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.css.IStyleSheet. La interfaz StyleSheet es la interfaz base abstracta para cualquier tipo de hoja de estilo. Representa una única hoja de estilo asociada a un documento estructurado. En HTML, la interfaz StyleSheet representa una hoja de estilo externa incluida mediante el elemento HTML LINK o un elemento STYLE en línea. En XML, esta interfaz representa una hoja de estilo externa incluida mediante una instrucción de procesamiento de hoja de estilo. Las hojas de estilo CSS implementarán además la interfaz más especializada CSSStyleSheet."
type: docs

url: /es/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

La interfaz StyleSheet es la interfaz base abstracta para cualquier tipo de hoja de estilo. Representa una única hoja de estilo asociada a un documento estructurado. En HTML, la interfaz StyleSheet representa una hoja de estilo externa, incluida mediante el elemento HTML LINK, o un elemento STYLE en línea. En XML, esta interfaz representa una hoja de estilo externa, incluida mediante una instrucción de procesamiento de hoja de estilo. Las hojas de estilo CSS implementarán además la interfaz más especializada [`CSSStyleSheet`](../icssstylesheet/).

Véase también la [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) La propiedad href de la interfaz `StyleSheet` devuelve la ubicación de la hoja de estilo. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) La propiedad media de la interfaz `StyleSheet` especifica el medio de destino previsto para la información de estilo. Es un objeto de solo lectura, similar a un array, [`MediaList`](../imedialist/) y puede eliminarse con deleteMedium() y añadirse con appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) El nodo que asocia esta hoja de estilo con el documento. Para HTML, puede ser el elemento LINK o STYLE correspondiente. Para XML, puede ser la instrucción de procesamiento de enlace. Para hojas de estilo incluidas por otras hojas de estilo, el valor de este atributo es null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) Para los lenguajes de hojas de estilo que admiten el concepto de inclusión de hojas de estilo, este atributo representa la hoja de estilo que incluye, si existe. Si la hoja de estilo es una hoja de nivel superior, o el lenguaje de hojas de estilo no admite inclusión, el valor de este atributo es null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) La propiedad title de la interfaz `StyleSheet` devuelve el título descriptivo de la hoja de estilo actual. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Esto especifica el lenguaje de la hoja de estilo para esta hoja de estilo. El lenguaje de la hoja de estilo se especifica como un tipo de contenido (p. ej., "text/css"). |

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Ver también

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
