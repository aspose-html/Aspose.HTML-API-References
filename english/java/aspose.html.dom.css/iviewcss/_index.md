---
title: IViewCSS Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.IViewCSS interface. The IViewCSS interface represents an extension to the Window object that give an access to the values of all CSS properties of an element
type: docs

url: /java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

The IViewCSS interface represents an extension to the Window object that give an access to the values of all CSS properties of an element.

The CSS Style for a given element can be obtained using the IViewCSS.GetComputedStyle() method.

```java
public interface IViewCSS : IAbstractView
```

## Methods

| Name | Description |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | The IViewCSS.getComputedStyle() method returns an object containing the values of all CSS properties of an element, after applying active stylesheets and resolving any basic computation those values may contain. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | The IViewCSS.getComputedStyle() method returns an object containing the values of all CSS properties of an element, after applying active stylesheets and resolving any basic computation those values may contain. |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### See Also

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
