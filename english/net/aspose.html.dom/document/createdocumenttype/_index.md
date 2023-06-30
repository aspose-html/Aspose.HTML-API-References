---
title: Document.CreateDocumentType
second_title: Aspose.HTML for .NET API Reference
description: Document method. The method returns a DocumentType object which can either be used with DOMImplementation.createDocument upon document creation or can be put into the document via methods like Node.insertBefore or Node.replaceChild
type: docs
weight: 840
url: /net/aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

The method returns a [`DocumentType`](../../documenttype/) object which can either be used with DOMImplementation.createDocument upon document creation or can be put into the document via methods like Node.insertBefore() or Node.replaceChild().

```csharp
public DocumentType CreateDocumentType(string name, string publicId, string systemId, 
    string internalSubset)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Is a DOMString containing the qualified name, like svg:svg. |
| publicId | String | Is a DOMString containing the PUBLIC identifier. |
| systemId | String | Is a DOMString containing the SYSTEM identifiers. |
| internalSubset | String | The internal subset. |

### Return Value

The [`DocumentType`](../../documenttype/).

## Examples

```csharp
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### See Also

* class [DocumentType](../../documenttype/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
