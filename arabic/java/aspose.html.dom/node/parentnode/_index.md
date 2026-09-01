---
title: "Node.ParentNode"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية Node. الخاصية parentNode للقراءة فقط في واجهة Node تُرجع الأب للعقدة المحددة في شجرة DOM."
type: docs

url: /ar/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

الخاصية parentNode للقراءة فقط في واجهة Node تُرجع الأب للعقدة المحددة في شجرة DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

عقدة Node هي الأب للعقدة الحالية. أب العنصر هو عقدة [`Element`](../../element/)، أو عقدة [`Document`](../../document/)، أو عقدة [`DocumentFragment`](../../documentfragment/).

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
