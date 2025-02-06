---
title: Node.BaseURI
second_title: Aspose.HTML for Java API Reference
description: Node property. The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node
type: docs
weight: 20
url: /java/com.aspose.html.dom/node/baseuri/
---
## Node.BaseURI property

The read-only baseURI property of the Node interface returns the absolute base URL of the document containing the node.

The base URL is used to resolve relative URLs when the browser needs to obtain an absolute URL, for example when processing the HTML img element's src attribute or the xlink:href or href attributes in SVG.

```java
public String BaseURI { get; }
```

### Property Value

The baseURI getter returns this’s node document’s document base URL, serialized.

## Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-baseuri](https://dom.spec.whatwg.org/#dom-node-baseuri).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### See Also

* class [Node](../)
* package [com.aspose.html.dom](../../node/)
* package [Aspose.HTML](../../../)
