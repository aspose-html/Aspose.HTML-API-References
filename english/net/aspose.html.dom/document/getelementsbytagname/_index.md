---
title: Document.GetElementsByTagName
second_title: Aspose.HTML for .NET API Reference
description: Document GetElementsByTagName method. This method returns an HTMLCollection of elements with the given tag name
type: docs
weight: 980
url: /net/aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

This method returns an [`HTMLCollection`](../../../aspose.html.collections/htmlcollection/) of elements with the given tag name.

The complete document is searched, including the root node. The returned [`HTMLCollection`](../../../aspose.html.collections/htmlcollection/) is live, meaning that it updates itself automatically to stay in sync with the DOM tree without having to call this method again.

```csharp
public HTMLCollection GetElementsByTagName(string tagname)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tagname | String | A string representing the name of the elements. The special string "*" represents all elements. |

### Return Value

A live [`HTMLCollection`](../../../aspose.html.collections/htmlcollection/) of found elements in the order they appear in the tree.

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

### See Also

* class [HTMLCollection](../../../aspose.html.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
