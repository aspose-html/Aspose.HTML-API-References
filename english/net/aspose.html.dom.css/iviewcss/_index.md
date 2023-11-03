---
title: IViewCSS Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.IViewCSS interface. The IViewCSS interface represents an extension to the Window object that give an access to the values of all CSS properties of an element
type: docs
weight: 770
url: /net/aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

The IViewCSS interface represents an extension to the Window object that give an access to the values of all CSS properties of an element.

The CSS Style for a given element can be obtained using the IViewCSS.GetComputedStyle() method.

```csharp
public interface IViewCSS : IAbstractView
```

## Methods

| Name | Description |
| --- | --- |
| [GetComputedStyle](../../aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | The IViewCSS.getComputedStyle() method returns an object containing the values of all CSS properties of an element, after applying active stylesheets and resolving any basic computation those values may contain. |
| [GetComputedStyle](../../aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, string) | The IViewCSS.getComputedStyle() method returns an object containing the values of all CSS properties of an element, after applying active stylesheets and resolving any basic computation those values may contain. |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### See Also

* interface [IAbstractView](../../aspose.html.dom.views/iabstractview/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
