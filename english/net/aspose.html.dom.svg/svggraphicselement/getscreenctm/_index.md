---
title: SVGGraphicsElement.GetScreenCTM
second_title: Aspose.HTML for .NET API Reference
description: SVGGraphicsElement method. Returns the transformation matrix from current user units i.e. after application of the transform attribute if any to the parent user agents notice of a pixel. For display devices ideally this represents a physical screen pixel. For other devices or environments where physical pixel sizes are not known then an algorithm similar to the CSS2 definition of a pixel can be used instead. Note that null is returned if this element is not hooked into the document tree. This method would have been more aptly named as getClientCTM but the name getScreenCTM is kept for historical reasons
type: docs
weight: 90
url: /net/aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Returns the transformation matrix from current user units (i.e., after application of the ‘transform’ attribute, if any) to the parent user agent's notice of a "pixel". For display devices, ideally this represents a physical screen pixel. For other devices or environments where physical pixel sizes are not known, then an algorithm similar to the CSS2 definition of a "pixel" can be used instead. Note that null is returned if this element is not hooked into the document tree. This method would have been more aptly named as getClientCTM, but the name getScreenCTM is kept for historical reasons.

```csharp
public SVGMatrix GetScreenCTM()
```

### Return Value

An SVGMatrix object that defines the given transformation matrix.

### See Also

* class [SVGMatrix](../../../aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Html.Dom.Svg](../../svggraphicselement/)
* assembly [Aspose.HTML](../../../)
