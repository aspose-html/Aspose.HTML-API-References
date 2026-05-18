---
title: "Node.ParentNode"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Node प्रॉपर्टी। पढ़ने‑के‑लिए‑केवल parentNode प्रॉपर्टी Node इंटरफ़ेस की निर्दिष्ट नोड का पैरेंट DOM ट्री में लौटाती है।"
type: docs

url: /hi/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

पढ़ने‑के‑लिए‑केवल parentNode प्रॉपर्टी Node इंटरफ़ेस की निर्दिष्ट नोड का पैरेंट DOM ट्री में लौटाती है।

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

एक Node जो वर्तमान नोड का पैरेंट है। किसी तत्व का पैरेंट एक [`Element`](../../element/) नोड, एक [`Document`](../../document/) नोड, या एक [`DocumentFragment`](../../documentfragment/) नोड हो सकता है।

## टिप्पणियाँ

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### संबंधित देखें

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
