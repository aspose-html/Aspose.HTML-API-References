---
title: "IXPathResult.IterateNext"
second_title: "Aspose.HTML for Java API 참조"
description: "IXPathResult 메서드. 노드 집합에서 다음 노드를 반복해서 반환하며, 더 이상 노드가 없으면 null을 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

노드 집합을 순회하며 다음 노드를 반환합니다. 더 이상 노드가 없으면 `null`을 반환합니다.

```java
public Node IterateNext()
```

### 반환 값

다음 노드를 반환합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: `resultType`이 `UnorderedNodeIterator` 유형이거나 `OrderedNodeIterator` 유형이 아닐 경우 발생합니다. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: 결과가 반환된 이후 문서가 변경되었습니다. |

### 또 보기

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
