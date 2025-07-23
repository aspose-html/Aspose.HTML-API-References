---
title: ICSSRuleList Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSRuleList interface. The CSSRuleList interface provides the abstraction of an ordered collection of CSS rules
type: docs
weight: 650
url: /net/aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

The CSSRuleList interface provides the abstraction of an ordered collection of CSS rules.

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.html.dom.css/icssrulelist/item/) { get; } | Used to retrieve a CSS rule by method item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). The order in this collection represents the order of the rules in the CSS style sheet. If index is greater than or equal to the number of rules in the list, this returns null. |
| [Length](../../aspose.html.dom.css/icssrulelist/length/) { get; } | The number of CSSRules in the list. The range of valid child rule indices is 0 to length-1 inclusive. |

### See Also

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
