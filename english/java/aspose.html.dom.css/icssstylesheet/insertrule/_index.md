---
title: ICSSStyleSheet.InsertRule
second_title: Aspose.HTML for Java API Reference
description: ICSSStyleSheet method. The CSSStyleSheet.insertRule method inserts a new CSS rule into the current style sheet with some restrictions
type: docs
weight: 40
url: /java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

The CSSStyleSheet.insertRule() method inserts a new CSS rule into the current style sheet, with some restrictions.

Note: Although insertRule() is exclusively a method of [`CSSStyleSheet`](../), it actually inserts the rule into CSSStyleSheet.cssRules — its internal [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rule | String | A String containing the rule to be inserted. What the inserted rule must contain depends on its type: |
| index | Int32 | A positive integer less than or equal to stylesheet.cssRules.length, representing the newly inserted rule's position in CSSStyleSheet.cssRules. The default is 0. |

### Return Value

The newly inserted rule's index within the stylesheet's rule-list.

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### See Also

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
