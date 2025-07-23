---
title: Document.GetElementsByClassName
second_title: Aspose.HTML for .NET API Reference
description: Document GetElementsByClassName method. This method returns an array-like object of all child elements which have all the given class names
type: docs
weight: 970
url: /net/aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

This method returns an array-like object of all child elements which have all the given class name(s).

When called on the document object, the complete document is searched, including the root node. You may also call this method on any element; it will return only elements which are descendants of the specified root element with the given class name(s).

```csharp
public HTMLCollection GetElementsByClassName(string classNames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classNames | String | The string that contains an unordered set of unique space-separated tokens representing classes (class names) |

### Return Value

A live [`HTMLCollection`](../../../aspose.html.collections/htmlcollection/) of found elements.

## Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

### See Also

* class [HTMLCollection](../../../aspose.html.collections/htmlcollection/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
