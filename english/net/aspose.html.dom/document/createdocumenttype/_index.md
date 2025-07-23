---
title: Document.CreateDocumentType
second_title: Aspose.HTML for .NET API Reference
description: Document CreateDocumentType method. The method returns a DocumentType object which can either be used with CreateDocument upon document creation or can be put into the document via methods like InsertBefore or ReplaceChild
type: docs
weight: 840
url: /net/aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

The method returns a [`DocumentType`](../../documenttype/) object which can either be used with [`CreateDocument`](../../idomimplementation/createdocument/) upon document creation or can be put into the document via methods like [`InsertBefore`](../../node/insertbefore/) or [`ReplaceChild`](../../node/replacechild/).

```csharp
public DocumentType CreateDocumentType(string name, string publicId, string systemId, 
    string internalSubset)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Is a DOMString containing the qualified name, like svg:svg. |
| publicId | String | Is a DOMString containing the PUBLIC identifier. |
| systemId | String | Is a DOMString containing the SYSTEM identifier. |
| internalSubset | String | The internal subset. |

### Return Value

The [`DocumentType`](../../documenttype/).

### See Also

* class [DocumentType](../../documenttype/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
