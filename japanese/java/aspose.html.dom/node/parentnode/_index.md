---
title: "Node.ParentNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node プロパティ。Node インターフェイスの読み取り専用 parentNode プロパティは、DOM ツリー内で指定されたノードの親ノードを返します"
type: docs

url: /ja/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

Node インターフェイスの読み取り専用 parentNode プロパティは、DOM ツリー内で指定されたノードの親ノードを返します。

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

現在のノードの親である Node です。要素の親は、[`Element`](../../element/) ノード、[`Document`](../../document/) ノード、または [`DocumentFragment`](../../documentfragment/) ノードのいずれかです。

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
