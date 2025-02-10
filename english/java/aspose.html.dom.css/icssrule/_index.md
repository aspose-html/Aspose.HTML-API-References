---
title: ICSSRule Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.ICSSRule interface. The CSSRule interface is the abstract base interface for any type of CSS statement. This includes both rule sets and at-rules. An implementation is expected to preserve all rules specified in a CSS style sheet even if the rule is not recognized by the parser. Unrecognized rules are represented using the interface
type: docs

url: /java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

The CSSRule interface is the abstract base interface for any type of CSS statement. This includes both rule sets and at-rules. An implementation is expected to preserve all rules specified in a CSS style sheet, even if the rule is not recognized by the parser. Unrecognized rules are represented using the interface.

```java
public interface ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) If this rule is contained inside another rule (e.g. a style rule inside an @media block), this is the containing rule. If this rule is not nested inside any other rules, this returns null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) The parentStyleSheet property of the `CSSRule` interface returns the [`StyleSheet`](../istylesheet/) object in which the current rule is defined. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) The type of the rule, as defined [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). The expectation is that binding-specific casting methods can be used to cast down from an instance of the CSSRule interface to the specific derived interface implied by the type. |

### See Also

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
