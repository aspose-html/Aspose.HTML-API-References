---
title: ICSSKeyframesRule Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSKeyframesRule interface. The CSSKeyframesRule interface represents a complete set of keyframes for a single animation
type: docs
weight: 600
url: /net/aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

The CSSKeyframesRule interface represents a complete set of keyframes for a single animation

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icsskeyframesrule/cssrules/) { get; } | This attribute gives access to the keyframes in the list |
| [Name](../../aspose.html.dom.css/icsskeyframesrule/name/) { get; } | This attribute is the name of the keyframes, used by the ‘animation-name’ property. |

## Methods

| Name | Description |
| --- | --- |
| [AppendRule](../../aspose.html.dom.css/icsskeyframesrule/appendrule/)(*string*) | The appendRule method appends the passed CSSKeyframeRule into the list at the passed key |
| [DeleteRule](../../aspose.html.dom.css/icsskeyframesrule/deleterule/)(*string*) | The deleteRule method deletes the CSSKeyframeRule with the passed key. If a rule with this key does not exist, the method does nothing |
| [FindRule](../../aspose.html.dom.css/icsskeyframesrule/findrule/)(*string*) | The findRule method returns the rule with a key matching the passed key. If no such rule exists, a null value is returned |

### See Also

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
