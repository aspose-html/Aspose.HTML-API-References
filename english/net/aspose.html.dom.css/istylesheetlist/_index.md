---
title: IStyleSheetList Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.IStyleSheetList interface. The StyleSheetList interface represents a list of CSSStyleSheet objects. An instance of this object can be returned by Document.styleSheets
type: docs
weight: 770
url: /net/aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

The StyleSheetList interface represents a list of [`CSSStyleSheet`](../icssstylesheet/) objects. An instance of this object can be returned by [`Document.styleSheets`](../../aspose.html.dom/document/stylesheets/).

The object’s supported property indices are the numbers in the range zero to one less than the number of CSS style sheets represented by the collection. If there are no such CSS style sheets, then there are no supported property indices.

```csharp
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Members
## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.html.dom.css/istylesheetlist/item/) { get; } | The item(index) method must return the indexth [`CSS style sheet`](../icssstylesheet/) in the collection. If there is no indexth object in the collection, then the method must return null. |
| [Length](../../aspose.html.dom.css/istylesheetlist/length/) { get; } | The length attribute must return the number of CSS style sheets represented by the collection. The range of valid child stylesheet indices is 0 to length-1 inclusive. |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### See Also

* interface [ICSSStyleSheet](../icssstylesheet/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
