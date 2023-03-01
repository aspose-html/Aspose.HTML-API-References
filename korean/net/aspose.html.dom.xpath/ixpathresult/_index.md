---
title: Interface IXPathResult
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.XPath.IXPathResult 상호 작용. XPath 결과 인터페이스는 특정 노드의 컨텍스트 내에서 XPath 1.0 식의 평가 결과를 나타냅니다. XPath 식의 평가 는 다양한 결과 유형을 초래할 수 있으므로 이 개체를 사용하면 결과의 유형과 값을 검색하고 조작할 수 있습니다.
type: docs
weight: 2600
url: /ko/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPath 결과` 인터페이스는 특정 노드의 컨텍스트 내에서 XPath 1.0 식의 평가 결과를 나타냅니다. XPath 식의 평가 는 다양한 결과 유형을 초래할 수 있으므로 이 개체를 사용하면 결과의 유형과 값을 검색하고 조작할 수 있습니다.

```csharp
public interface IXPathResult
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | 이 부울 결과의 값입니다. |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | 반복자가 무효화되었음을 나타냅니다. 참이면`결과 유형` 는`정렬되지 않은 노드 반복자` 입력하거나`OrderedNodeIterator` 유형 및 이 결과가 반환된 이후 문서가 수정되었습니다. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | 이 숫자 결과의 값입니다. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult 에 정의된 대로 이 결과의 유형을 나타내는 코드입니다.[`XPathResultType`](../xpathresulttype/) 열거형. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | 이 단일 노드 결과의 값은 다음과 같을 수 있습니다.`없는` . |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | 결과 스냅샷의 노드 수입니다. snapshotItem 인덱스의 유효한 값은 다음과 같습니다.`0` 에게`스냅샷 길이-1` 포함. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | 이 문자열 결과의 값입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | 노드 집합에서 다음 노드를 반복하고 반환하거나`없는` 더 이상 노드가 없는 경우. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | 반환`색인` 스냅샷 컬렉션의 th 항목입니다. 만약에`색인` 보다 크거나 목록의 노드 수와 같으면 이 메서드는 다음을 반환합니다.`없는` . 반복자 결과와 달리 스냅샷이 무효화되지는 않지만 변경된 경우 현재 문서와 일치하지 않을 수 있습니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* 집회 [Aspose.HTML](../../)


