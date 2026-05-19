---
title: "Node.ChildNodes"
second_title: "Aspose.HTML for Java API 참조"
description: "Node 속성. Node 인터페이스의 읽기 전용 childNodes 속성은 지정된 요소의 자식 노드들에 대한 실시간 NodeList를 반환하며, 첫 번째 자식 노드에 인덱스 0이 할당됩니다. 자식 노드에는 요소, 텍스트 및 주석이 포함됩니다."
type: docs

url: /ko/java/com.aspose.html.dom/node/childnodes/
---
## Node.ChildNodes property

Node 인터페이스의 읽기 전용 childNodes 속성은 지정된 요소의 자식 노드에 대한 실시간 [`NodeList`](../../../com.aspose.html.collections/nodelist/)를 반환하며, 첫 번째 자식 노드에 인덱스 0이 할당됩니다. 자식 노드에는 요소, 텍스트 및 주석이 포함됩니다.

참고: [`NodeList`](../../../com.aspose.html.collections/nodelist/)가 실시간이라는 것은 새로운 자식이 추가되거나 제거될 때마다 그 내용이 변경된다는 의미입니다.

```java
public NodeList ChildNodes { get; }
```

### Property Value

노드의 자식을 포함하는 실시간 [`NodeList`](../../../com.aspose.html.collections/nodelist/).

참고: childNodes에 대한 여러 호출은 동일한 [`NodeList`](../../../com.aspose.html.collections/nodelist/)를 반환합니다.

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-childnodes](https://dom.spec.whatwg.org/#dom-node-childnodes).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 또 보기

* class [NodeList](../../../com.aspose.html.collections/nodelist/)
* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
