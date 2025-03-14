---
title: ICSSRuleList Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSRuleList interface. A CSSRuleList represents an ordered collection of read-only CSSRule objects
type: docs
weight: 650
url: /net/aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

A CSSRuleList represents an ordered collection of read-only [`CSSRule`](../icssrule/) objects.

While the CSSRuleList object is read-only, and cannot be directly modified, it is considered a live object, as the content can change over time.

To edit the underlying rules returned by [`CSSRule`](../icssrule/) objects, use CSSStyleSheet.insertRule() and CSSStyleSheet.deleteRule(), which are methods of [`CSSStyleSheet`](../icssstylesheet/).

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Members
## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.html.dom.css/icssrulelist/item/) { get; } | Used to retrieve a CSS rule by method item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). The order in this collection represents the order of the rules in the CSS style sheet. If index is greater than or equal to the number of rules in the list, this returns null. |
| [Length](../../aspose.html.dom.css/icssrulelist/length/) { get; } | The length property of the `CSSRuleList` interface returns the number of [`CSSRule`](../icssrule/) objects in the list. |

### See Also

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
