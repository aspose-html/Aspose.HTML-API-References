---
title: IStyleSheet.ParentStyleSheet
second_title: Aspose.HTML for .NET API Reference
description: IStyleSheet ParentStyleSheet property. For style sheet languages that support the concept of style sheet inclusion this attribute represents the including style sheet if one exists. If the style sheet is a top-level style sheet or the style sheet language does not support inclusion the value of this attribute is null
type: docs
weight: 50
url: /net/aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

For style sheet languages that support the concept of style sheet inclusion, this attribute represents the including style sheet, if one exists. If the style sheet is a top-level style sheet, or the style sheet language does not support inclusion, the value of this attribute is null.

```csharp
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

The parentStyleSheet attribute must return the parent [`CSS style sheet`](../../icssstylesheet/).

## Remarks

This property returns null if the current stylesheet is a top-level stylesheet or if stylesheet inclusion is not supported.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### See Also

* interface [IStyleSheet](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
