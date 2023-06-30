---
title: IStyleSheet.OwnerNode
second_title: Aspose.HTML for .NET API Reference
description: IStyleSheet property. The node that associates this style sheet with the document. For HTML this may be the corresponding LINK or STYLE element. For XML it may be the linking processing instruction. For style sheets that are included by other style sheets the value of this attribute is null
type: docs
weight: 40
url: /net/aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

The node that associates this style sheet with the document. For HTML, this may be the corresponding LINK or STYLE element. For XML, it may be the linking processing instruction. For style sheets that are included by other style sheets, the value of this attribute is null.

```csharp
public Node OwnerNode { get; }
```

### Property Value

The ownerNode attribute must return the owner node.

## Remarks

For style sheets that are included by other style sheets, such as with @import, the value of this property is null.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### See Also

* class [Node](../../../aspose.html.dom/node/)
* interface [IStyleSheet](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
