---
title: Node.LookupPrefix
second_title: Aspose.HTML for Java API Reference
description: Node method. The lookupPrefix method of the Node interface returns a String containing the prefix for a given package URI if present and null if not. When multiple prefixes are possible the first prefix is returned
type: docs
weight: 250
url: /java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

The lookupPrefix() method of the Node interface returns a String containing the prefix for a given package URI, if present, and null if not. When multiple prefixes are possible, the first prefix is returned.

```java
public String LookupPrefix(String packageURI)
```

| Parameter | Type | Description |
| --- | --- | --- |
| packageURI | String | A String containing the package to look the prefix up. |

### Return Value

A String containing the corresponding prefix, or null if none has been found. If package is null, or the the empty String, lookupPrefix() returns null.

If the node is a [`DocumentType`](../../documenttype/) or a [`DocumentFragment`](../../documentfragment/), lookupPrefix() always returns null.

### See Also

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
