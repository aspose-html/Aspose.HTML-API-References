---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.HTML for Java API 참조"
description: "NodeFilter 메서드. 지정된 노드가 TreeWalker 또는 NodeIterator의 논리적 뷰에서 보이는지 테스트합니다. 이 함수는 TreeWalker와 NodeIterator 구현에 의해 호출되며 일반적으로 사용자 코드에서 직접 호출되지 않습니다. 동일한 필터를 사용하여 애플리케이션 로직을 제어하고 싶다면 직접 호출할 수도 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

TreeWalker 또는 NodeIterator의 논리적 뷰에서 지정된 노드가 보이는지 테스트합니다. 이 함수는 TreeWalker와 NodeIterator 구현에 의해 호출되며, 일반적으로 사용자 코드에서 직접 호출되지 않습니다. (동일한 필터를 사용해 자체 애플리케이션 로직을 안내하고 싶다면 직접 호출할 수도 있습니다.)

```java
public abstract short AcceptNode(Node n)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| n | Node | 필터를 통과하는지 확인할 노드. |

### 반환 값

위에서 정의한 대로 노드가 허용, 거부 또는 건너뛰기 중 어느 것인지 결정하는 상수.

### 또 보기

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.dom.traversal.filters](../../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../../)
