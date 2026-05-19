---
title: "Node.ParentNode"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство Node. Только для чтения свойство parentNode интерфейса Node возвращает родительский узел указанного узла в дереве DOM"
type: docs

url: /ru/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

Только для чтения свойство parentNode интерфейса Node возвращает родительский узел указанного узла в дереве DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

Узел Node, являющийся родителем текущего узла. Родителем элемента может быть узел [`Element`](../../element/), узел [`Document`](../../document/) или узел [`DocumentFragment`](../../documentfragment/).

## Примечания

Ссылка:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### См. также

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
