---
title: IViewCSS.GetComputedStyle
second_title: Aspose.HTML for .NET API Reference
description: IViewCSS GetComputedStyle method. The IViewCSS.getComputedStyle method returns an object containing the values of all CSS properties of an element after applying active stylesheets and resolving any basic computation those values may contain
type: docs
weight: 10
url: /net/aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(*[Element](../../../aspose.html.dom/element/)*) {#getcomputedstyle}

The IViewCSS.getComputedStyle() method returns an object containing the values of all CSS properties of an element, after applying active stylesheets and resolving any basic computation those values may contain.

Individual CSS property values are accessed through APIs provided by the object, or by indexing with CSS property names.

```csharp
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | Element | The [`Element`](../../../aspose.html.dom/element/) for which to get the computed style. This parameter cannot be null. |

### Return Value

The returned style is a live [`CSSStyleDeclaration`](../../icssstyledeclaration/) object, which updates automatically when the element's styles are changed.

### Exceptions

| exception | condition |
| --- | --- |
| TypeError | If the passed object is not an Element or the pseudoElt is not a valid pseudo-element selector. |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### See Also

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../aspose.html.dom/element/)
* interface [IViewCSS](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)

---

## GetComputedStyle(*[Element](../../../aspose.html.dom/element/), string*) {#getcomputedstyle_1}

The IViewCSS.getComputedStyle() method returns an object containing the values of all CSS properties of an element, after applying active stylesheets and resolving any basic computation those values may contain.

Individual CSS property values are accessed through APIs provided by the object, or by indexing with CSS property names.

```csharp
public ICSSStyleDeclaration GetComputedStyle(Element element, string pseudoElement)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | Element | The [`Element`](../../../aspose.html.dom/element/) for which to get the computed style. This parameter cannot be null. |
| pseudoElement | String | A string specifying the pseudo-element to match. Omitted (or null) for real elements. |

### Return Value

The returned style is a live [`CSSStyleDeclaration`](../../icssstyledeclaration/) object, which updates automatically when the element's styles are changed.

### Exceptions

| exception | condition |
| --- | --- |
| TypeError | If the passed object is not an Element or the pseudoElt is not a valid pseudo-element selector. |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### See Also

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../aspose.html.dom/element/)
* interface [IViewCSS](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
