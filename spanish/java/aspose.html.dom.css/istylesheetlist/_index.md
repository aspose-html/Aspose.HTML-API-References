---
title: "Interfaz IStyleSheetList"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.css.IStyleSheetList interface. La interfaz StyleSheetList representa una lista de objetos CSSStyleSheet. Una instancia de este objeto puede ser devuelta por Document.styleSheets."
type: docs

url: /es/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

La interfaz StyleSheetList representa una lista de objetos [`CSSStyleSheet`](../icssstylesheet/). Una instancia de este objeto puede ser devuelta por [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

Los índices de propiedades admitidos por el objeto son los números en el rango de cero a uno menos que el número de hojas de estilo CSS representadas por la colección. Si no existen esas hojas de estilo CSS, entonces no hay índices de propiedades admitidos.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) El método item(index) debe devolver la hoja de estilo [`CSS style sheet`](../icssstylesheet/) en la posición índice de la colección. Si no hay un objeto en esa posición índice en la colección, el método debe devolver null. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) El atributo length debe devolver el número de hojas de estilo CSS representadas por la colección. El rango de índices válidos de hojas de estilo secundarias es de 0 a length-1 inclusive. |

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### Ver también

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
