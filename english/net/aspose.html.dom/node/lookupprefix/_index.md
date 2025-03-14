---
title: Node.LookupPrefix
second_title: Aspose.HTML for .NET API Reference
description: Node LookupPrefix method. The lookupPrefix method of the Node interface returns a String containing the prefix for a given namespace URI if present and null if not. When multiple prefixes are possible the first prefix is returned
type: docs
weight: 250
url: /net/aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

The lookupPrefix() method of the Node interface returns a String containing the prefix for a given namespace URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned.

```csharp
public string LookupPrefix(string namespaceURI)
```

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | String | A string containing the namespace to look the prefix up. |

### Return Value

A String containing the corresponding prefix, or null if none has been found. If namespace is null, or the the empty string, lookupPrefix() returns null.

If the node is a [`DocumentType`](../../documenttype/) or a [`DocumentFragment`](../../documentfragment/), lookupPrefix() always returns null.

### See Also

* class [Node](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
