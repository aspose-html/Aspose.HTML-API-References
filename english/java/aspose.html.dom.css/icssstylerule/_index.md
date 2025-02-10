---
title: ICSSStyleRule Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.ICSSStyleRule interface. The CSSStyleRule interface represents a single CSS style rule. The selectorText attribute on getting must return the result of serializing the associated group of selectors
type: docs
weight: 670
url: /java/com.aspose.html.dom.css/icssstylerule/
---
## ICSSStyleRule interface

The CSSStyleRule interface represents a single CSS style rule. The selectorText attribute, on getting, must return the result of serializing the associated group of selectors

```java
public interface ICSSStyleRule : ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
| [getSelectorText](../../com.aspose.html.dom.css/icssstylerule/selectortext/) The textual representation of the selector for the rule set. The implementation may have stripped out insignificant whitespace while parsing the selector. |
| [getStyle](../../com.aspose.html.dom.css/icssstylerule/style/) The read-only style property is the [`CSSStyleDeclaration`](../icssstyledeclaration/) interface for the declaration block of the `CSSStyleRule`. |

### See Also

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
