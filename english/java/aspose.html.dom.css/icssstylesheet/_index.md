---
title: ICSSStyleSheet Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.ICSSStyleSheet interface. The CSSStyleSheet interface represents a single CSS stylesheet and lets you inspect and modify the list of rules contained in the stylesheet. It inherits properties and methods from its parent IStyleSheet
type: docs

url: /java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

The CSSStyleSheet interface represents a single CSS stylesheet, and lets you inspect and modify the list of rules contained in the stylesheet. It inherits properties and methods from its parent, [`IStyleSheet`](../istylesheet/).

A stylesheet consists of a collection of [`ICSSRule`](../icssrule/) objects representing each of the rules in the stylesheet. The rules are contained in a [`ICSSRuleList`](../icssrulelist/), which can be obtained from the stylesheet's cssRules property.

For example, one rule might be a [`ICSSStyleRule`](../icssstylerule/) object containing a style such as

```java
h1, h2 {   font-size: 16pt; }
```

Another rule might be an at-rule such as @import or @media, and so forth.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Properties

| Name | Description |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) The read-only CSSStyleSheet property cssRules returns a live [`CSSRuleList`](../icssrulelist/) which provides a real-time, up-to-date list of every CSS rule which comprises the stylesheet. Each item in the list is a [`CSSRule`](../icssrule/) defining a single rule. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) The read-only CSSStyleSheet property ownerRule returns the [`CSSImportRule`](../icssimportrule/) corresponding to the @import at-rule which imported the stylesheet into the document. If the stylesheet wasn't imported into the document using @import, the returned value is null. |

## Methods

| Name | Description |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | The `CSSStyleSheet` method deleteRule() removes a rule from the stylesheet object. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | The CSSStyleSheet.insertRule() method inserts a new CSS rule into the current style sheet, with some restrictions. |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### See Also

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
