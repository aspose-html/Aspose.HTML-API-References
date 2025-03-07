---
title: MultipartContent Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Net.MultipartContent class. Represents a multipart/ content
type: docs
weight: 4220
url: /net/aspose.html.net/multipartcontent/
---
## MultipartContent class

Represents a multipart/* content.

```csharp
public class MultipartContent : Content, IEnumerable<Content>
```

## Constructors

| Name | Description |
| --- | --- |
| [MultipartContent](multipartcontent/#constructor)() | Create a new instance of the `MultipartContent` class. |
| [MultipartContent](multipartcontent/#constructor_1)(*string*) | Create a new instance of the `MultipartContent` class with subtype. |
| [MultipartContent](multipartcontent/#constructor_2)(*string, string*) | Create a new instance of the `MultipartContent` class with subtype and boundary. |

## Properties

| Name | Description |
| --- | --- |
| [Headers](../../aspose.html.net/content/headers/) { get; } | Gets the HTTP content headers. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Add](../../aspose.html.net/multipartcontent/add/)(*[Content](../content/)*) | Add a new content to the `MultipartContent` |
| [Dispose](../../aspose.html.net/content/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetEnumerator](../../aspose.html.net/multipartcontent/getenumerator/)() | Returns an enumerator that iterates through a collection. |
| [ReadAsByteArray](../../aspose.html.net/content/readasbytearray/)() | Serialize the HTTP content and return a byte array that represents the content. |
| [ReadAsStream](../../aspose.html.net/content/readasstream/)() | Serialize the HTTP content and return a stream that represents the content. |
| [ReadAsString](../../aspose.html.net/content/readasstring/)() | Serialize the HTTP content and return a string that represents the content. |

### See Also

* class [Content](../content/)
* namespace [Aspose.Html.Net](../../aspose.html.net/)
* assembly [Aspose.HTML](../../)
