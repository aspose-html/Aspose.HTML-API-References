---
title: ICSSRuleList Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Css.ICSSRuleList interface. A CSSRuleList represents an ordered collection of read-only CSSRule objects
type: docs
weight: 490
url: /net/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

A CSSRuleList represents an ordered collection of read-only [`CSSRule`](../icssrule/) objects.

While the CSSRuleList object is read-only, and cannot be directly modified, it is considered a live object, as the content can change over time.

To edit the underlying rules returned by [`CSSRule`](../icssrule/) objects, use CSSStyleSheet.insertRule() and CSSStyleSheet.deleteRule(), which are methods of [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Properties

| Name | Description |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Used to retrieve a CSS rule by method item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). The order in this collection represents the order of the rules in the CSS style sheet. If index is greater than or equal to the number of rules in the list, this returns null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) The length property of the `CSSRuleList` interface returns the number of [`CSSRule`](../icssrule/) objects in the list. |

### See Also

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.Dom.Css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
