---
title: IStyleSheet Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Css.IStyleSheet interface. The StyleSheet interface is the abstract base interface for any type of style sheet. It represents a single style sheet associated with a structured document. In HTML the StyleSheet interface represents either an external style sheet included via the HTML LINK element or an inline STYLE element. In XML this interface represents an external style sheet included via a style sheet processing instruction. CSS style sheets will further implement the more specialized CSSStyleSheet interface
type: docs
weight: 600
url: /java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

The StyleSheet interface is the abstract base interface for any type of style sheet. It represents a single style sheet associated with a structured document. In HTML, the StyleSheet interface represents either an external style sheet, included via the HTML LINK element, or an inline STYLE element. In XML, this interface represents an external style sheet, included via a style sheet processing instruction. CSS style sheets will further implement the more specialized [`CSSStyleSheet`](../icssstylesheet/) interface.

See also the [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Properties

| Name | Description |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) The href property of the `StyleSheet` interface returns the location of the style sheet. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) The media property of the `StyleSheet` interface specifies the intended destination media for style information. It is a read-only, array-like [`MediaList`](../imedialist/) object and can be removed with deleteMedium() and added with appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) The node that associates this style sheet with the document. For HTML, this may be the corresponding LINK or STYLE element. For XML, it may be the linking processing instruction. For style sheets that are included by other style sheets, the value of this attribute is null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) For style sheet languages that support the concept of style sheet inclusion, this attribute represents the including style sheet, if one exists. If the style sheet is a top-level style sheet, or the style sheet language does not support inclusion, the value of this attribute is null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) The title property of the `StyleSheet` interface returns the advisory title of the current style sheet. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) This specifies the style sheet language for this style sheet. The style sheet language is specified as a content type (e.g. "text/css"). |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### See Also

* package [com.aspose.html.Dom.Css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
