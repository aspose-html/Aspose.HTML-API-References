---
title: ICSSStyleSheet.CSSRules
second_title: Aspose.HTML for Java API Reference
description: ICSSStyleSheet property. The read-only CSSStyleSheet property cssRules returns a live CSSRuleList which provides a real-time up-to-date list of every CSS rule which comprises the stylesheet. Each item in the list is a CSSRule defining a single rule
type: docs
weight: 10
url: /java/com.aspose.html.dom.css/icssstylesheet/cssrules/
---
## ICSSStyleSheet.CSSRules property

The read-only CSSStyleSheet property cssRules returns a live [`CSSRuleList`](../../icssrulelist/) which provides a real-time, up-to-date list of every CSS rule which comprises the stylesheet. Each item in the list is a [`CSSRule`](../../icssrule/) defining a single rule.

```java
public ICSSRuleList CSSRules { get; }
```

### Property Value

A live-updating [`CSSRuleList`](../../icssrulelist/) containing each of the CSS rules making up the stylesheet. Each entry in the rule list is a [`CSSRule`](../../icssrule/) object describing one rule making up the stylesheet.

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-cssrules](https://drafts.csswg.org/cssom/#dom-cssstylesheet-cssrules) – The CSSOM definition.

### See Also

* interface [ICSSRuleList](../../icssrulelist/)
* interface [ICSSStyleSheet](../)
* package [com.aspose.html.Dom.Css](../../icssstylesheet/)
* package [Aspose.HTML](../../../)
