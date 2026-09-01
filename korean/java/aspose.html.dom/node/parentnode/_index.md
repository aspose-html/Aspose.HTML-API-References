---
title: "Node.ParentNode"
second_title: "Java용 Aspose.HTML API 참조"
description: "Node 속성. Node 인터페이스의 읽기 전용 parentNode 속성은 DOM 트리에서 지정된 노드의 부모를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

Node 인터페이스의 읽기 전용 parentNode 속성은 DOM 트리에서 지정된 노드의 부모를 반환합니다.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

현재 노드의 부모인 Node입니다. 요소의 부모는 [`Element`](../../element/) 노드, [`Document`](../../document/) 노드, 또는 [`DocumentFragment`](../../documentfragment/) 노드 중 하나입니다.

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
