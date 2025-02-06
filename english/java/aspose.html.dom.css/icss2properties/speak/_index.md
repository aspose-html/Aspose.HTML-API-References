---
title: ICSS2Properties.Speak
second_title: Aspose.HTML for Java API Reference
description: ICSS2Properties property. This property specifies whether text will be rendered aurally and if so in what manner somewhat analogous to the display property. The possible values are
type: docs
weight: 1000
url: /java/com.aspose.html.dom.css/icss2properties/speak/
---
## ICSS2Properties.Speak property

This property specifies whether text will be rendered aurally and if so, in what manner (somewhat analogous to the ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) property). The possible values are:

none - Suppresses aural rendering so that the element requires no time to render. Note, however, that descendants may override this value and will be spoken. (To be sure to suppress rendering of an element and its descendants, use the ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) property).normal - Uses language-dependent pronunciation rules for rendering an element and its children.spell-out - Spells the text one letter at a time (useful for acronyms and abbreviations).

```java
public String Speak { get; set; }
```

### Return Value

speak property

### See Also

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../icss2properties/)
* package [Aspose.HTML](../../../)
