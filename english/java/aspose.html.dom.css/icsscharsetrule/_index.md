---
title: ICSSCharsetRule Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Css.ICSSCharsetRule interface. The CSSCharsetRule interface represents a charset rule in a CSS style sheet. The value of the encoding attribute does not affect the encoding of text data in the DOM objects this encoding is always UTF-16. After a stylesheet is loaded the value of the encoding attribute is the value found in the charset rule. If there was no charset in the original document then no CSSCharsetRule is created. The value of the encoding attribute may also be used as a hint for the encoding used on serialization of the style sheet
type: docs
weight: 390
url: /net/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

The CSSCharsetRule interface represents a @charset rule in a CSS style sheet. The value of the encoding attribute does not affect the encoding of text data in the DOM objects; this encoding is always UTF-16. After a stylesheet is loaded, the value of the encoding attribute is the value found in the @charset rule. If there was no @charset in the original document, then no CSSCharsetRule is created. The value of the encoding attribute may also be used as a hint for the encoding used on serialization of the style sheet.

```java
public interface ICSSCharsetRule : ICSSRule
```

## Properties

| Name | Description |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### See Also

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.Dom.Css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
