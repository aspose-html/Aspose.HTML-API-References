---
title: ICSSMediaRule Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSMediaRule interface. The CSSMediaRule interface represents a media rule in a CSS style sheet. A media rule can be used to delimit style rules for specific media types
type: docs
weight: 620
url: /net/aspose.html.dom.css/icssmediarule/
---
## ICSSMediaRule interface

The CSSMediaRule interface represents a @media rule in a CSS style sheet. A @media rule can be used to delimit style rules for specific media types.

```csharp
public interface ICSSMediaRule : ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssmediarule/cssrules/) { get; } | The cssRules property of the CSSGroupingRule interface returns a [`CSSRuleList`](../icssrulelist/) containing a collection of [`CSSRule`](../icssrule/) objects. |
| [Media](../../aspose.html.dom.css/icssmediarule/media/) { get; } | The read-only media property of the `CSSMediaRule` interface MediaList represents the intended destination medium for style information. |

## Methods

| Name | Description |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssmediarule/deleterule/)(long) | The deleteRule() method of the CSSGroupingRule interface removes a CSS rule from a list of child CSS rules. |
| [InsertRule](../../aspose.html.dom.css/icssmediarule/insertrule/)(string, long) | The insertRule() method of the CSSGroupingRule interface adds a new CSS rule to a list of CSS rules. |

### See Also

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
