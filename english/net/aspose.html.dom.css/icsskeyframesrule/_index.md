---
title: ICSSKeyframesRule Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.ICSSKeyframesRule interface. The name property of the CSSKeyframeRule interface gets and sets the name of the animation as used by the animation-name property
type: docs
weight: 590
url: /net/aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

The name property of the CSSKeyframeRule interface gets and sets the name of the animation as used by the animation-name property.

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icsskeyframesrule/cssrules/) { get; } | The read-only cssRules property of the [`CSSKeyframeRule`](../icsskeyframerule/) interface returns a [`CSSRuleList`](../icssrulelist/) containing the rules in the keyframes at-rule. |
| [Name](../../aspose.html.dom.css/icsskeyframesrule/name/) { get; } | The name property of the [`CSSKeyframeRule`](../icsskeyframerule/) interface gets and sets the name of the animation as used by the animation-name property. |

## Methods

| Name | Description |
| --- | --- |
| [AppendRule](../../aspose.html.dom.css/icsskeyframesrule/appendrule/)(string) | The appendRule method appends the passed [`CSSKeyframeRule`](../icsskeyframerule/) at the end of the keyframes rule collection. |
| [DeleteRule](../../aspose.html.dom.css/icsskeyframesrule/deleterule/)(string) | The deleteRule method deletes the [`CSSKeyframeRule`](../icsskeyframerule/) with the passed key. If a rule with this key does not exist, the method does nothing |
| [FindRule](../../aspose.html.dom.css/icsskeyframesrule/findrule/)(string) | The findRule method returns the rule with a key matching the passed key. If no such rule exists, a null value is returned |

### See Also

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
