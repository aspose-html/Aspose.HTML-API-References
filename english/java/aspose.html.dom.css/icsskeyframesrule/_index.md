---
title: ICSSKeyframesRule Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Css.ICSSKeyframesRule interface. The name property of the CSSKeyframeRule interface gets and sets the name of the animation as used by the animation-name property
type: docs
weight: 440
url: /net/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

The name property of the CSSKeyframeRule interface gets and sets the name of the animation as used by the animation-name property.

```java
public interface ICSSKeyframesRule : ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) The read-only cssRules property of the [`CSSKeyframeRule`](../icsskeyframerule/) interface returns a [`CSSRuleList`](../icssrulelist/) containing the rules in the keyframes at-rule. |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) The name property of the [`CSSKeyframeRule`](../icsskeyframerule/) interface gets and sets the name of the animation as used by the animation-name property. |

## Methods

| Name | Description |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | The appendRule method appends the passed [`CSSKeyframeRule`](../icsskeyframerule/) at the end of the keyframes rule collection. |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | The deleteRule method deletes the [`CSSKeyframeRule`](../icsskeyframerule/) with the passed key. If a rule with this key does not exist, the method does nothing |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | The findRule method returns the rule with a key matching the passed key. If no such rule exists, a null value is returned |

### See Also

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.Dom.Css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
