---
title: IStyleSheetList.Item
second_title: Aspose.HTML for .NET API Reference
description: IStyleSheetList property. The itemindex method must return the indexth CSS style sheet in the collection. If there is no indexth object in the collection then the method must return null
type: docs
weight: 10
url: /net/aspose.html.dom.css/istylesheetlist/item/
---
## IStyleSheetList indexer

The item(index) method must return the indexth [`CSS style sheet`](../../icssstylesheet/) in the collection. If there is no indexth object in the collection, then the method must return null.

```csharp
public ICSSStyleSheet this[int index] { get; }
```

### Return Value

A [`CSSStyleSheet`](../../icssstylesheet/) object, or null if one does not exist for this index.

### Property Value

An integer which is the index of the item in the collection to be returned.

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheetlist-item](https://drafts.csswg.org/cssom/#dom-stylesheetlist-item) – The CSSOM definition.

### See Also

* interface [ICSSStyleSheet](../../icssstylesheet/)
* interface [IStyleSheetList](../)
* namespace [Aspose.Html.Dom.Css](../../istylesheetlist/)
* assembly [Aspose.HTML](../../../)
