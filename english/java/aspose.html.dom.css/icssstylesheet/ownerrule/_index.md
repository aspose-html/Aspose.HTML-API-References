---
title: ICSSStyleSheet.OwnerRule
second_title: Aspose.HTML for Java API Reference
description: ICSSStyleSheet property. The read-only CSSStyleSheet property ownerRule returns the CSSImportRule corresponding to the import at-rule which imported the stylesheet into the document. If the stylesheet wasnt imported into the document using import the returned value is null
type: docs
weight: 20
url: /java/com.aspose.html.dom.css/icssstylesheet/ownerrule/
---
## ICSSStyleSheet.OwnerRule property

The read-only CSSStyleSheet property ownerRule returns the [`CSSImportRule`](../../icssimportrule/) corresponding to the @import at-rule which imported the stylesheet into the document. If the stylesheet wasn't imported into the document using @import, the returned value is null.

```java
public ICSSRule OwnerRule { get; }
```

### Property Value

A CSSImportRule corresponding to the @import rule which imported the stylesheet into the document. If the stylesheet wasn't imported into the document using @import, the returned value is null.

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-ownerrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-ownerrule) – The CSSOM definition.

### See Also

* interface [ICSSRule](../../icssrule/)
* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
