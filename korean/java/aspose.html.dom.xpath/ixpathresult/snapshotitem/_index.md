---
title: "IXPathResult.SnapshotItem"
second_title: "Java용 Aspose.HTML API 참조"
description: "IXPathResult method. 스냅샷 컬렉션에서 index번째 항목을 반환합니다. index가 리스트의 노드 수보다 크거나 같으면 이 메서드는 null을 반환합니다. 반복자 결과와 달리 스냅샷은 무효화되지 않지만 문서가 변형된 경우 현재 문서와 일치하지 않을 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

`index`번째 스냅샷 컬렉션 항목을 반환합니다. `index`가 리스트의 노드 수보다 크거나 같으면 이 메서드는 `null`을 반환합니다. 반복자 결과와 달리 스냅샷은 무효화되지 않지만, 문서가 변경되면 현재 문서와 일치하지 않을 수 있습니다.

```java
public Node SnapshotItem(int index)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| index | Int32 | 스냅샷 컬렉션의 인덱스. |

### 반환 값

`NodeList`에서 `index`번째 위치에 있는 노드이며, 유효한 인덱스가 아닌 경우 `null`입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: `resultType`이 `UnorderedNodeSnapshot` 유형 또는 `OrderedNodeSnapshot` 유형이 아닌 경우 발생합니다. |

### 또 보기

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
