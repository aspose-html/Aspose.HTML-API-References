---
title: "Interfaz ICSSStyleSheet"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.css.ICSSStyleSheet. La interfaz CSSStyleSheet representa una hoja de estilo CSS única y le permite inspeccionar y modificar la lista de reglas contenidas en la hoja de estilo. Hereda propiedades y métodos de su padre IStyleSheet"
type: docs

url: /es/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

La interfaz CSSStyleSheet representa una hoja de estilo CSS única, y le permite inspeccionar y modificar la lista de reglas contenidas en la hoja de estilo. Hereda propiedades y métodos de su padre, [`IStyleSheet`](../istylesheet/).

Una hoja de estilo consta de una colección de objetos [`ICSSRule`](../icssrule/) que representan cada una de las reglas en la hoja de estilo. Las reglas están contenidas en una [`ICSSRuleList`](../icssrulelist/), que puede obtenerse de la propiedad cssRules de la hoja de estilo.

Por ejemplo, una regla podría ser un objeto [`ICSSStyleRule`](../icssstylerule/) que contiene un estilo como

```java
h1, h2 {   font-size: 16pt; }
```

Otra regla podría ser una regla at-rule como @import o @media, etc.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) La propiedad de solo lectura cssRules del CSSStyleSheet devuelve una [`CSSRuleList`](../icssrulelist/) en vivo que proporciona una lista en tiempo real y actualizada de cada regla CSS que compone la hoja de estilo. Cada elemento de la lista es un [`CSSRule`](../icssrule/) que define una única regla. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) La propiedad de solo lectura ownerRule del CSSStyleSheet devuelve el [`CSSImportRule`](../icssimportrule/) correspondiente a la regla at-rule @import que importó la hoja de estilo al documento. Si la hoja de estilo no fue importada al documento usando @import, el valor devuelto es null. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | El método `CSSStyleSheet` deleteRule() elimina una regla del objeto hoja de estilo. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | El método CSSStyleSheet.insertRule() inserta una nueva regla CSS en la hoja de estilo actual, con algunas restricciones. |

## Observaciones

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referencia

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### Ver también

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
