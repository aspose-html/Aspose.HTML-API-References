---
title: IXPathResult.SnapshotItem
second_title: .NET API 참조용 Aspose.HTML
description: IXPathResult 방법. 반환색인 스냅샷 컬렉션의 th 항목입니다. 만약에색인 보다 크거나 목록의 노드 수와 같으면 이 메서드는 다음을 반환합니다.없는 . 반복자 결과와 달리 스냅샷이 무효화되지는 않지만 변경된 경우 현재 문서와 일치하지 않을 수 있습니다.
type: docs
weight: 90
url: /ko/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

반환`색인` 스냅샷 컬렉션의 th 항목입니다. 만약에`색인` 보다 크거나 목록의 노드 수와 같으면 이 메서드는 다음을 반환합니다.`없는` . 반복자 결과와 달리 스냅샷이 무효화되지는 않지만 변경된 경우 현재 문서와 일치하지 않을 수 있습니다.

```csharp
public Node SnapshotItem(int index)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 스냅샷 컬렉션을 인덱싱합니다. |

### 반환 값

노드는`색인` 의 위치`노드 목록` , 또는`없는` 유효한 인덱스가 아닌 인 경우.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: 발생한 경우`결과 유형` 가 아닙니다.`정렬되지 않은 노드스냅샷` 입력하거나`주문된 노드 스냅샷` 유형. |

### 또한보십시오

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* 네임스페이스 [Aspose.Html.Dom.XPath](../../ixpathresult/)
* 집회 [Aspose.HTML](../../../)


