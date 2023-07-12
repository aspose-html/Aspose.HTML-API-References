---
title: IStyleSheet.Media
second_title: Aspose.HTML for .NET API Reference
description: IStyleSheet property. The media property of the StyleSheet interface specifies the intended destination media for style information. It is a read-only array-like MediaList object and can be removed with deleteMedium and added with appendMedium
type: docs
weight: 30
url: /net/aspose.html.dom.css/istylesheet/media/
---
## IStyleSheet.Media property

The media property of the [`StyleSheet`](../) interface specifies the intended destination media for style information. It is a read-only, array-like [`MediaList`](../../imedialist/) object and can be removed with deleteMedium() and added with appendMedium().

```csharp
public IMediaList Media { get; }
```

### Property Value

The media attribute must return the [`MediaList`](../../imedialist/) object associated with the CSS style sheet.

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-media](https://drafts.csswg.org/cssom/#dom-stylesheet-media) – The CSSOM definition.

### See Also

* interface [IMediaList](../../imedialist/)
* interface [IStyleSheet](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
