---
title: IStyleSheet.Disabled
second_title: Aspose.HTML for Java API Reference
description: IStyleSheet property. The disabled property of the StyleSheet interface determines whether the style sheet is prevented from applying to the document
type: docs
weight: 10
url: /java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

The disabled property of the [`StyleSheet`](../) interface determines whether the style sheet is prevented from applying to the document.

A style sheet may be disabled by manually setting this property to true or if it's an inactive alternative style sheet. Note that disabled == false does not guarantee the style sheet is applied (it could be removed from the document, for instance).

Modifying this attribute may cause a new resolution of style for the document. A stylesheet only applies if both an appropriate medium definition is present and the disabled attribute is false. So, if the media doesn't apply to the current user agent, the disabled attribute is ignored.

```java
public bool Disabled { get; set; }
```

### Return Value

The disabled attribute, on getting, must return true if the disabled flag is set, or false otherwise. On setting, the disabled attribute must set the disabled flag if the new value is true, or unset the disabled flag otherwise.

### Property Value

The disabled attribute, on getting, must return true if the disabled flag is set, or false otherwise. On setting, the disabled attribute must set the disabled flag if the new value is true, or unset the disabled flag otherwise.

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### See Also

* interface [IStyleSheet](../)
* package [com.aspose.html.Dom.Css](../../istylesheet/)
* package [Aspose.HTML](../../../)
